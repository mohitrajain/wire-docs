# Summary

* [Wire-docs](README.md)
* [Installation](how-to/install/README.md)
  * [How to plan an installation](how-to/install/planning.md)
  * [Version requirements](how-to/install/version-requirements.md)
  * [Dependencies on operator’s machine](how-to/install/dependencies.md)
  * [How to install kubernetes (Demo)](how-to/install/kubernetes.md)
  * [How to install wire-server using Helm (Demo)](how-to/install/helm.md)
  * [Introduction](how-to/install/prod-intro.md)
  * [How to install kubernetes and databases](how-to/install/ansible-VMs.md)
  * [How to configure AWS services](how-to/install/aws-prod.md)
  * [How to install wire-server using Helm](how-to/install/helm-prod.md)
  * [Infrastructure configuration](how-to/install/infrastructure-configuration.md)
  * [How to monitor wire-server](how-to/install/monitoring.md)
  * [How to see centralized logs for wire-server](how-to/install/logging.md)
  * [Ingress-controller (getting traffic in)](how-to/install/ingress.md)
  * [Web app settings](how-to/install/web-app-settings.md)
  * [Installing Conference Calling 2.0 (aka SFT)](how-to/install/sft.md)
  * [Installing Restund](how-to/install/restund.md)
  * [Configure TLS ciphers](how-to/install/tls.md)
  * [Managing authentication with ansible](how-to/install/ansible-authentication.md)
  * [Using tinc](how-to/install/ansible-tinc.md)
  * [Troubleshooting during installation](how-to/install/troubleshooting.md)
  * [Verifying your installation](how-to/install/post-install.md)
* [Administration](how-to/administrate/README.md)
  * [kubernetes](how-to/administrate/kubernetes/README.md)
  * [Backup and disaster recovery](how-to/administrate/backup-disaster-recovery.md)
  * [Cassandra](how-to/administrate/cassandra.md)
  * [Elasticsearch](how-to/administrate/elasticsearch.md)
  * [Etcd](how-to/administrate/etcd.md)
  * [General - Linux](how-to/administrate/general-linux.md)
  * [Minio](how-to/administrate/minio.md)
  * [Operational procedures](how-to/administrate/operations.md)
  * [Restund (TURN)](how-to/administrate/restund.md)
  * [Investigative tasks (e.g. searching for users as server admin)](how-to/administrate/users.md)
* [Reference](understand/README.md)
  * [Architecture Overview](understand/overview.md)
  * [Single Sign-On and User Provisioning](understand/single-sign-on/README.md)
  * [Audio/video calling, restund servers (TURN/STUN)](understand/restund.md)
  * [Conference Calling 2.0 (aka SFT)](understand/sft.md)
  * [Federated Conference Calling](understand/sft.md#federated-conference-calling)
  * [Minio](understand/minio.md)
  * [Helm](understand/helm.md)
  * [Federation](understand/federation/README.md)
  * [Connecting Wire Clients](understand/associate/README.md)
  * [Client API documentation](understand/api-client-perspective/README.md)
  * [Crypto libraries and sources of randomness](understand/crypto-libs.md)
  * [Block personal user creation](understand/block-user-creation.md)
  * [Classified Domains](understand/classified-domains.md)
  * [Federation](understand/configure-federation.md)
  * [Installing and setting up Legal Hold](understand/legalhold.md)
  * [Messaging Layer Security (MLS)](understand/mls.md)
  * [User Searchability](understand/searchability.md)
  * [Server and team feature settings](understand/team-feature-settings.md)
* [Developer Notes](developer/README.md)
  * [Developer](developer/developer/README.md)
    * [API versioning](developer/developer/api-versioning.md)
    * [How to build wire-server](developer/developer/building.md)
    * [Writing code interacting with cassandra](developer/developer/cassandra-interaction.md)
    * [Changelog](developer/developer/changelog.md)
    * [Coding conventions](developer/developer/coding-conventions.md)
    * [Dependencies](developer/developer/dependencies.md)
    * [Editor setup](developer/developer/editor-setup.md)
    * [Features](developer/developer/features.md)
    * [Federation API Conventions](developer/developer/federation-api-conventions.md)
    * [Federation Design Aspects](developer/developer/federation-design-aspects.md)
    * [Developer how-to’s](developer/developer/how-to.md)
    * [Refactoring galley to support large conversations](developer/developer/large-conversations.md)
    * [Linting](developer/developer/linting.md)
    * [OpenTelemetry Instrumentation](developer/developer/open-telemetry.md)
    * [PR Guidelines](developer/developer/pr-guidelines.md)
    * [Internal processes](developer/developer/processes.md)
    * [Storing SCIM-related data](developer/developer/scim/storage.md)
    * [Servant](developer/developer/servant.md)
    * [Testing the wire-server Haskell code base](developer/developer/testing.md)
    * [Upgrading](developer/developer/upgrading.md)
  * [Reference](developer/reference/README.md)
    * [Config Options](developer/reference/config-options.md)
    * [Creating and populating conversations](developer/reference/conversation.md)
    * [Maintaining ElasticSearch](developer/reference/elastic-search.md)
    * [ElasticSearch migration instructions for release 2021-02-16](developer/reference/elasticsearch-migration-2021-02-16.md)
    * [Make docker and QEMU](developer/reference/make-docker-and-qemu.md)
    * [OAuth](developer/reference/oauth.md)
    * [SCIM tokens](developer/reference/provisioning/scim-token.md)
    * [RabbitMQ Consumer](developer/reference/rabbitmq-consumer.md)
    * [Spar braindump](developer/reference/spar-braindump.md)
    * [Legal hold](developer/reference/team/legalhold.md)
    * [User Activation](developer/reference/user/activation.md)
    * [Connection](developer/reference/user/connection.md)
    * [Connection backend internals](developer/reference/user/connection.md#connection-backend-internals)
    * [User Registration](developer/reference/user/registration.md)
    * [User Rich info](developer/reference/user/rich-info.md)
* [Security Responses](security-responses/README.md)
  * [2023-01-19 - Security Advisory: HTML Injection in wire.com](security-responses/2023-01-19\_html\_injection.md)
  * [2023-01-04 - Outage of wire.com caused by a DoS attack](security-responses/2023-01-04\_website\_outage.md)
  * [2022-11-01 - High Severity Vulnerability in OpenSSL](security-responses/2022-11-01\_openssl.md)
  * [2022-05-23 - wire.com website outage](security-responses/2022-05-23\_website\_outage.md)
  * [2022-02 - CVE-2021-44521 (Cassandra "user defined functions")](security-responses/2022-02-21\_cve-2021-44521.md)
  * [2021-12 - log4shell](security-responses/2021-12-15\_log4shell.md)
* [Release Notes](changelog/README.md)
  * [changelog](changelog/changelog.md)
