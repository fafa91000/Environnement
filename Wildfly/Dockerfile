FROM jboss/wildfly

# Ajouter un utilisateur administrateur
RUN /opt/jboss/wildfly/bin/add-user.sh admin admin --silent

# Ajout du driver PostgreSQL
ADD Configuration/* /opt/jboss/wildfly/tmp/
RUN /opt/jboss/wildfly/tmp/execute.sh

RUN rm -rf /opt/jboss/wildfly/standalone/configuration/standalone_xml_history/current/*

EXPOSE 8787

CMD ["/opt/jboss/wildfly/bin/standalone.sh", "--debug", "-b", "0.0.0.0", "-bmanagement", "0.0.0.0"]