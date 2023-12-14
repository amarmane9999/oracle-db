Repository based on followig resources

listerner.log error: https://linuxdatahub.com/openshift-run-container-as-root/
GIT Doc: https://github.com/oracle/docker-images/tree/main/OracleDatabase/SingleInstance#how-to-build-and-run
Article to run : https://dev.to/pazyp/oracle-19c-with-docker-36m5
Base Image to pull: https://github.com/oracle/container-images/pkgs/container/oraclelinux/147550728?tag=7-slim
Push to openshift Registry: https://cookbook.openshift.org/image-registry-and-image-streams/how-do-i-push-an-image-to-the-internal-image-registry.html


connecttion command:

sqlplus sys/orcl2@//oracledb.test-db.svc.cluster.local:1521/orcl1 as sysdba
sqlplus system/orcl@//localhost:1521/

sqlplus pdbadmin/orcl2@//localhost:1521/orcl3
