# Wazuh Yandex Cloud rules

Wazuh rules for Yandex cloud Audit Trails. Be careful all rules are POC how for integration between [Wazuh](https://wazuh.com/) and [Yandex Cloud](https://cloud.yandex.com/)
. As well rules will not work without Pygoscelis integration and Kibana application. Pygoscelis image for Yandex Cloud will be announced soon

## Disclaimer
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

## Rules for security events

yandex_audit_trails_rules.xml  - [Audit Trails events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#audit-trails)

yandex_certificate_manager_rules.xml - [Certificate Manager events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#certificate-manager)

yandex_clickhouse_rules.xml - [Managed Service for ClickHouse events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#managed-service-for-clickhouse)

yandex_cloud_logging_rules.xml - [Cloud Logging events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#cloud-logging-name)

yandex_common_rules.xml - Unauthorized events

yandex_compute_cloud_rules.xml - [Compute Cloud events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#compute)

yandex_iam_rules.xml - [Certificate Manager events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#certificate-manager)

yandex_kms_rules.xml - [Identity and Access Management events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#iam)

yandex_lockbox_rules.xml - [Yandex Lockbox events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#lockbox)

yandex_mongodb_rules.xml - [Managed Service for MongoDB events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#managed-service-for-mongodb)

yandex_mysql_rules.xml - [Managed Service for MySQL events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#managed-service-for-mysql)

yandex_network_loadbalancer_rules.xml - [Network Load Balancer events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#network-load-balancer)

yandex_object_storage.xml - [Object Storage events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#objstorage)

yandex_postgresql_rules.xml - [Managed Service for PostgreSQL events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#managed-service-for-postgresql)

yandex_redis_rules.xml - [Managed Service for Redis events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#managed-service-for-redis)

yandex_resource_manager_rules.xml - [Resource Manager events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#resmgr)

yandex_vpc_rules.xml - [Virtual Private Cloud events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#vpc)

yandex_ybd_rules.xml - [YDB events](https://cloud.yandex.com/en/docs/audit-trails/concepts/events#ydb)

## License
[The 3-Clause BSD License](https://opensource.org/licenses/BSD-3-Clause)

## Maintainer

[pyToshka](https://github.com/pyToshka)
