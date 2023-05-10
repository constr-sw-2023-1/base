FROM jboss/keycloak:latest

ADD . /tmp

ENV KEYCLOAK_USER=admin
ENV KEYCLOAK_PASSWORD=a12345678
ENV KEYCLOAK_FRONTEND_URL=http://localhost:8090/auth


# RUN /opt/jboss/keycloak/bin/standalone.sh \
#     -Dkeycloak.migration.action=export \
#     -Dkeycloak.migration.provider=singleFile -Dkeycloak.migration.file=/tmp/constr-sw-2023-1.json \
#     -Dkeycloak.migration.realmName=Constr-sw-2023-1 \
#     -Dkeycloak.migration.usersExportStrategy=REALM_FILE
