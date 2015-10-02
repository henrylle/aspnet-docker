FROM henrylle/aspnet5:v5

COPY ./AppAutomatedBuild/src/AppAutomatedBuild/ /app
WORKDIR /app

RUN ["dnu", "restore"]

EXPOSE 5001

ENTRYPOINT ["dnx", "kestrel"]