## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | 5.8.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 5.8.0 |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_zsquad-assets"></a> [zsquad-assets](#module\_zsquad-assets) | ../../modules/zsquad-assets | n/a |
| <a name="module_zsquad-atom"></a> [zsquad-atom](#module\_zsquad-atom) | ../../modules/zsquad-atom | n/a |
| <a name="module_zsquad-atomapi"></a> [zsquad-atomapi](#module\_zsquad-atomapi) | ../../modules/zsquad-atomapi | n/a |
| <a name="module_zsquad-audit"></a> [zsquad-audit](#module\_zsquad-audit) | ../../modules/zsquad-audit | n/a |
| <a name="module_zsquad-bastion"></a> [zsquad-bastion](#module\_zsquad-bastion) | ../../modules/zsquad-bastion | n/a |
| <a name="module_zsquad-cassandra"></a> [zsquad-cassandra](#module\_zsquad-cassandra) | ../../modules/zsquad-cassandra | n/a |
| <a name="module_zsquad-cassandra-cluster"></a> [zsquad-cassandra-cluster](#module\_zsquad-cassandra-cluster) | ../../modules/zsquad-cassandra-cluster | n/a |
| <a name="module_zsquad-connect-far"></a> [zsquad-connect-far](#module\_zsquad-connect-far) | ../../modules/zsquad-connect-far | n/a |
| <a name="module_zsquad-connect-sec-far"></a> [zsquad-connect-sec-far](#module\_zsquad-connect-sec-far) | ../../modules/zsquad-connect-sec-far | n/a |
| <a name="module_zsquad-connectapi-far"></a> [zsquad-connectapi-far](#module\_zsquad-connectapi-far) | ../../modules/zsquad-connectapi-far | n/a |
| <a name="module_zsquad-connectapi-sec-far"></a> [zsquad-connectapi-sec-far](#module\_zsquad-connectapi-sec-far) | ../../modules/zsquad-connectapi-sec-far | n/a |
| <a name="module_zsquad-connectui"></a> [zsquad-connectui](#module\_zsquad-connectui) | ../../modules/zsquad-connectui | n/a |
| <a name="module_zsquad-es"></a> [zsquad-es](#module\_zsquad-es) | ../../modules/zsquad-es | n/a |
| <a name="module_zsquad-es-sec"></a> [zsquad-es-sec](#module\_zsquad-es-sec) | ../../modules/zsquad-es-sec | n/a |
| <a name="module_zsquad-gateway"></a> [zsquad-gateway](#module\_zsquad-gateway) | ../../modules/zsquad-gateway | n/a |
| <a name="module_zsquad-gateway-api"></a> [zsquad-gateway-api](#module\_zsquad-gateway-api) | ../../modules/zsquad-gateway-api | n/a |
| <a name="module_zsquad-iam"></a> [zsquad-iam](#module\_zsquad-iam) | ../../modules/zsquad-iam | n/a |
| <a name="module_zsquad-importer"></a> [zsquad-importer](#module\_zsquad-importer) | ../../modules/zsquad-importer | n/a |
| <a name="module_zsquad-lambda-function"></a> [zsquad-lambda-function](#module\_zsquad-lambda-function) | ../../modules/zsquad-lambda-function | n/a |
| <a name="module_zsquad-migrate"></a> [zsquad-migrate](#module\_zsquad-migrate) | ../../modules/zsquad-migrate | n/a |
| <a name="module_zsquad-network"></a> [zsquad-network](#module\_zsquad-network) | ../../modules/zsquad-network | n/a |
| <a name="module_zsquad-nginx"></a> [zsquad-nginx](#module\_zsquad-nginx) | ../../modules/zsquad-nginx | n/a |
| <a name="module_zsquad-rds"></a> [zsquad-rds](#module\_zsquad-rds) | ../../modules/zsquad-rds | n/a |
| <a name="module_zsquad-redis"></a> [zsquad-redis](#module\_zsquad-redis) | ../../modules/zsquad-redis | n/a |
| <a name="module_zsquad-riak"></a> [zsquad-riak](#module\_zsquad-riak) | ../../modules/zsquad-riak | n/a |
| <a name="module_zsquad-riak-qua"></a> [zsquad-riak-qua](#module\_zsquad-riak-qua) | ../../modules/zsquad-riak-qua | n/a |
| <a name="module_zsquad-riak-qui"></a> [zsquad-riak-qui](#module\_zsquad-riak-qui) | ../../modules/zsquad-riak-qui | n/a |
| <a name="module_zsquad-riak-sec"></a> [zsquad-riak-sec](#module\_zsquad-riak-sec) | ../../modules/zsquad-riak-sec | n/a |
| <a name="module_zsquad-riak-sen"></a> [zsquad-riak-sen](#module\_zsquad-riak-sen) | ../../modules/zsquad-riak-sen | n/a |
| <a name="module_zsquad-riak-ter"></a> [zsquad-riak-ter](#module\_zsquad-riak-ter) | ../../modules/zsquad-riak-ter | n/a |
| <a name="module_zsquad-route53"></a> [zsquad-route53](#module\_zsquad-route53) | ../../modules/zsquad-route53 | n/a |
| <a name="module_zsquad-s3"></a> [zsquad-s3](#module\_zsquad-s3) | ../../modules/zsquad-s3 | n/a |
| <a name="module_zsquad-scale-support-instance"></a> [zsquad-scale-support-instance](#module\_zsquad-scale-support-instance) | ../../modules/zsquad-scale-support-instance | n/a |
| <a name="module_zsquad-secrets"></a> [zsquad-secrets](#module\_zsquad-secrets) | ../../modules/zsquad-secrets | n/a |
| <a name="module_zsquad-xray-all"></a> [zsquad-xray-all](#module\_zsquad-xray-all) | ../../modules/zsquad-xray-all | n/a |

## Resources

| Name | Type |
|------|------|
| [aws_iam_policy.ec2_snap_cleanup_policy](https://registry.terraform.io/providers/hashicorp/aws/5.8.0/docs/resources/iam_policy) | resource |
| [aws_caller_identity.current](https://registry.terraform.io/providers/hashicorp/aws/5.8.0/docs/data-sources/caller_identity) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_ami_retention_days"></a> [ami\_retention\_days](#input\_ami\_retention\_days) | ami deletion period | `number` | `30` | no |
| <a name="input_application_id"></a> [application\_id](#input\_application\_id) | Application\_ID | `string` | `"Zephyr_Squad"` | no |
| <a name="input_autoscaling_ami_id"></a> [autoscaling\_ami\_id](#input\_autoscaling\_ami\_id) | autoscaling\_ami\_id | `string` | `"ami-0b250f625dc7f2bc9"` | no |
| <a name="input_autoscaling_iam_instance_profile"></a> [autoscaling\_iam\_instance\_profile](#input\_autoscaling\_iam\_instance\_profile) | autoscaling\_iam\_instance\_profile | `string` | `"arn:aws:iam::955541768397:instance-profile/ecsInstanceRole"` | no |
| <a name="input_aws_profile_name"></a> [aws\_profile\_name](#input\_aws\_profile\_name) | aws\_profile\_name | `string` | `"qaenv"` | no |
| <a name="input_bastion_instance_type"></a> [bastion\_instance\_type](#input\_bastion\_instance\_type) | bastion\_instance\_type | `string` | `"t3.large"` | no |
| <a name="input_business_unit"></a> [business\_unit](#input\_business\_unit) | Business\_Unit | `string` | `"Zephyr_Squad"` | no |
| <a name="input_ca_cert_identifier"></a> [ca\_cert\_identifier](#input\_ca\_cert\_identifier) | ca\_cert\_identifier | `string` | `"rds-ca-ecc384-g1"` | no |
| <a name="input_cache_policy_id"></a> [cache\_policy\_id](#input\_cache\_policy\_id) | cache\_policy\_id | `string` | `"965ada96-2b90-4c65-87bc-7152626658f3"` | no |
| <a name="input_cassandra-cluster-instance-count"></a> [cassandra-cluster-instance-count](#input\_cassandra-cluster-instance-count) | cassandra-instance-count | `string` | `"2"` | no |
| <a name="input_cassandra_cluster_instance_type"></a> [cassandra\_cluster\_instance\_type](#input\_cassandra\_cluster\_instance\_type) | cassandra\_instance\_type | `string` | `"m5.xlarge"` | no |
| <a name="input_cassandra_instance_type"></a> [cassandra\_instance\_type](#input\_cassandra\_instance\_type) | cassandra\_instance\_type | `string` | `"t3.medium"` | no |
| <a name="input_cidr_blocks"></a> [cidr\_blocks](#input\_cidr\_blocks) | cidr blocks | `list` | <pre>[<br/>  "10.2.0.0/16"<br/>]</pre> | no |
| <a name="input_connect_autoscaling_instance_type"></a> [connect\_autoscaling\_instance\_type](#input\_connect\_autoscaling\_instance\_type) | connect\_autoscaling\_instance\_type | `string` | `"t3.small"` | no |
| <a name="input_connect_ui_http_version"></a> [connect\_ui\_http\_version](#input\_connect\_ui\_http\_version) | connect\_ui\_http\_version | `string` | `"http2"` | no |
| <a name="input_connect_ui_minimum_tls_protocol_version"></a> [connect\_ui\_minimum\_tls\_protocol\_version](#input\_connect\_ui\_minimum\_tls\_protocol\_version) | connect\_ui\_minimum\_tls\_protocol\_version | `string` | `"TLSv1.2_2019"` | no |
| <a name="input_connectui_alternate_domain_name"></a> [connectui\_alternate\_domain\_name](#input\_connectui\_alternate\_domain\_name) | connectui\_alternate\_domain\_name | `string` | `"zsqud-qabench-connectui.zephyr4jiracloud.com"` | no |
| <a name="input_connectui_s3_arn"></a> [connectui\_s3\_arn](#input\_connectui\_s3\_arn) | connectui\_s3\_arn | `string` | `"arn:aws:s3:::zsqud-qabench-connectui-s3"` | no |
| <a name="input_connectui_s3_id"></a> [connectui\_s3\_id](#input\_connectui\_s3\_id) | connectui\_s3\_id | `string` | `"zsqud-qabench-connectui-s3"` | no |
| <a name="input_connectui_s3_url"></a> [connectui\_s3\_url](#input\_connectui\_s3\_url) | connectui\_s3\_url | `string` | `"zsqud-qabench-connectui-s3.s3.us-west-2.amazonaws.com"` | no |
| <a name="input_daily_backup"></a> [daily\_backup](#input\_daily\_backup) | daily\_backup | `string` | `"Yes"` | no |
| <a name="input_default_ami"></a> [default\_ami](#input\_default\_ami) | n/a | `string` | `"ami-002ba162ca66775c0"` | no |
| <a name="input_delete_enabled"></a> [delete\_enabled](#input\_delete\_enabled) | deletion enable option | `bool` | `false` | no |
| <a name="input_dns_prefix"></a> [dns\_prefix](#input\_dns\_prefix) | DNS prefix for the xray | `string` | `"zsquad-qabench-xray"` | no |
| <a name="input_ec2_lambda_handler"></a> [ec2\_lambda\_handler](#input\_ec2\_lambda\_handler) | Handler for the Lambda function | `string` | `"function.lambda_handler"` | no |
| <a name="input_ec2_lambda_runtime"></a> [ec2\_lambda\_runtime](#input\_ec2\_lambda\_runtime) | Runtime for the Lambda function | `string` | `"python3.10"` | no |
| <a name="input_ec2_lambda_schedule_expression"></a> [ec2\_lambda\_schedule\_expression](#input\_ec2\_lambda\_schedule\_expression) | CloudWatch schedule expression | `string` | `"rate(1 day)"` | no |
| <a name="input_ec2_lambda_timeout"></a> [ec2\_lambda\_timeout](#input\_ec2\_lambda\_timeout) | set lambda timeout value | `number` | `900` | no |
| <a name="input_ecs_service_role_arn"></a> [ecs\_service\_role\_arn](#input\_ecs\_service\_role\_arn) | ecs\_service\_role\_arn | `string` | `"arn:aws:iam::955541768397:role/ecsServiceRole"` | no |
| <a name="input_ecs_task_execution_role"></a> [ecs\_task\_execution\_role](#input\_ecs\_task\_execution\_role) | ecs\_task\_execution\_role | `string` | `"arn:aws:iam::955541768397:role/ecsTaskExecutionRole"` | no |
| <a name="input_ecs_task_role_arn"></a> [ecs\_task\_role\_arn](#input\_ecs\_task\_role\_arn) | ecs\_task\_role\_arn | `string` | `"arn:aws:iam::955541768397:role/ecs-connect-role"` | no |
| <a name="input_efs_throughput_mode_migrate"></a> [efs\_throughput\_mode\_migrate](#input\_efs\_throughput\_mode\_migrate) | efs\_throughput\_mode\_migrate | `string` | `"bursting"` | no |
| <a name="input_email"></a> [email](#input\_email) | Email | `string` | `"sreenivas.narayan@smartbear.com"` | no |
| <a name="input_env"></a> [env](#input\_env) | env | `string` | `"zsquad-qabench"` | no |
| <a name="input_env_aws"></a> [env\_aws](#input\_env\_aws) | env\_aws | `string` | `"qabench"` | no |
| <a name="input_environment"></a> [environment](#input\_environment) | environment | `string` | `"QualityAssurance"` | no |
| <a name="input_environment_disable_api_termination"></a> [environment\_disable\_api\_termination](#input\_environment\_disable\_api\_termination) | environment\_disable\_api\_termination | `string` | `"false"` | no |
| <a name="input_es-instance-count"></a> [es-instance-count](#input\_es-instance-count) | es-instance-count | `string` | `"4"` | no |
| <a name="input_es-sec-instance-count"></a> [es-sec-instance-count](#input\_es-sec-instance-count) | es-sec-instance-count | `string` | `"3"` | no |
| <a name="input_gateway_alb_logs"></a> [gateway\_alb\_logs](#input\_gateway\_alb\_logs) | gateway\_alb\_logs | `bool` | `"false"` | no |
| <a name="input_gateway_db_url"></a> [gateway\_db\_url](#input\_gateway\_db\_url) | gateway\_db\_url | `string` | `"jdbc:mysql://rds-writer.zfjcloud.internal/qabenchtenantclustermap"` | no |
| <a name="input_gateway_image_name"></a> [gateway\_image\_name](#input\_gateway\_image\_name) | gateway\_image\_name | `string` | `"955541768397.dkr.ecr.us-west-2.amazonaws.com/gateway:current_componenst_build"` | no |
| <a name="input_hazelcast_config_path"></a> [hazelcast\_config\_path](#input\_hazelcast\_config\_path) | hazelcast\_config\_path | `string` | `"10.3.0.0"` | no |
| <a name="input_hazelcast_interface"></a> [hazelcast\_interface](#input\_hazelcast\_interface) | hazelcast\_interface | `string` | `"10.2.*.*"` | no |
| <a name="input_jcma_migrate_s3_storage_name"></a> [jcma\_migrate\_s3\_storage\_name](#input\_jcma\_migrate\_s3\_storage\_name) | jcma\_migrate\_s3\_storage\_name | `string` | `"squad-qa-jcma-migration-data"` | no |
| <a name="input_jcma_migrate_s3_storage_name_acceleration_status"></a> [jcma\_migrate\_s3\_storage\_name\_acceleration\_status](#input\_jcma\_migrate\_s3\_storage\_name\_acceleration\_status) | jcma\_migrate\_s3\_storage\_name\_acceleration\_status | `string` | `"Suspended"` | no |
| <a name="input_migrate-instance-count"></a> [migrate-instance-count](#input\_migrate-instance-count) | migrate-instance-count | `string` | `"2"` | no |
| <a name="input_migrate_instance_type"></a> [migrate\_instance\_type](#input\_migrate\_instance\_type) | migrate\_instance\_type | `string` | `"m5a.xlarge"` | no |
| <a name="input_owner"></a> [owner](#input\_owner) | Owner | `string` | `"Sreenivas Narayan"` | no |
| <a name="input_priv-subnet"></a> [priv-subnet](#input\_priv-subnet) | priv-subnet | `list` | <pre>[<br/>  "10.2.0.0/24",<br/>  "10.2.2.0/24"<br/>]</pre> | no |
| <a name="input_project"></a> [project](#input\_project) | project | `string` | `"zsquad-qabench"` | no |
| <a name="input_pub-subnet"></a> [pub-subnet](#input\_pub-subnet) | pub-subnet | `list` | <pre>[<br/>  "10.2.1.0/24",<br/>  "10.2.3.0/24"<br/>]</pre> | no |
| <a name="input_qa_ec2_instance_type"></a> [qa\_ec2\_instance\_type](#input\_qa\_ec2\_instance\_type) | qa\_ec2\_instance\_type | `string` | `"t3a.small"` | no |
| <a name="input_rds_db_one_engine_version"></a> [rds\_db\_one\_engine\_version](#input\_rds\_db\_one\_engine\_version) | rds\_db\_one\_engine\_version | `string` | `"8.0.mysql_aurora.3.05.2"` | no |
| <a name="input_rds_db_one_instance_class"></a> [rds\_db\_one\_instance\_class](#input\_rds\_db\_one\_instance\_class) | rds\_db\_one\_instance\_class | `string` | `"db.t3.large"` | no |
| <a name="input_rds_engine_version"></a> [rds\_engine\_version](#input\_rds\_engine\_version) | rds\_engine\_version | `string` | `"8.0.mysql_aurora.3.05.2"` | no |
| <a name="input_rds_redis_backup_retention_period"></a> [rds\_redis\_backup\_retention\_period](#input\_rds\_redis\_backup\_retention\_period) | rds\_redis\_backup\_retention\_period | `string` | `"1"` | no |
| <a name="input_redis_automatic_failover_enabled"></a> [redis\_automatic\_failover\_enabled](#input\_redis\_automatic\_failover\_enabled) | redis\_automatic\_failover\_enabled | `string` | `"false"` | no |
| <a name="input_redis_node_count"></a> [redis\_node\_count](#input\_redis\_node\_count) | redis\_node\_count | `string` | `"4"` | no |
| <a name="input_region"></a> [region](#input\_region) | region | `string` | `"us-west-2"` | no |
| <a name="input_riak-instance-count"></a> [riak-instance-count](#input\_riak-instance-count) | riak-instance-count | `string` | `"9"` | no |
| <a name="input_riak-qua-instance-count"></a> [riak-qua-instance-count](#input\_riak-qua-instance-count) | riak-qua-instance-count | `string` | `"9"` | no |
| <a name="input_riak-qua-instance-type"></a> [riak-qua-instance-type](#input\_riak-qua-instance-type) | riak-qua-instance-type | `string` | `"c7i.2xlarge"` | no |
| <a name="input_riak-qui-instance-count"></a> [riak-qui-instance-count](#input\_riak-qui-instance-count) | riak-qui-instance-count | `string` | `"9"` | no |
| <a name="input_riak-qui-instance-type"></a> [riak-qui-instance-type](#input\_riak-qui-instance-type) | riak-qui-instance-type | `string` | `"c7i.2xlarge"` | no |
| <a name="input_riak-sec-instance-count"></a> [riak-sec-instance-count](#input\_riak-sec-instance-count) | riak-sec-instance-count | `string` | `"9"` | no |
| <a name="input_riak-sec-instance-type"></a> [riak-sec-instance-type](#input\_riak-sec-instance-type) | riak-sec-instance-type | `string` | `"c6g.xlarge"` | no |
| <a name="input_riak-sen-instance-count"></a> [riak-sen-instance-count](#input\_riak-sen-instance-count) | riak-sen-instance-count | `string` | `"9"` | no |
| <a name="input_riak-sen-instance-type"></a> [riak-sen-instance-type](#input\_riak-sen-instance-type) | riak-sen-instance-type | `string` | `"c7i.2xlarge"` | no |
| <a name="input_riak-tertiary-instance-count"></a> [riak-tertiary-instance-count](#input\_riak-tertiary-instance-count) | riak-tertiary-instance-count | `string` | `"9"` | no |
| <a name="input_riak-tertiary-instance-type"></a> [riak-tertiary-instance-type](#input\_riak-tertiary-instance-type) | riak-tertiary-instance-type | `string` | `"c6g.12xlarge"` | no |
| <a name="input_riak_backup"></a> [riak\_backup](#input\_riak\_backup) | riak\_backup | `string` | `"Yes"` | no |
| <a name="input_riak_instance_type"></a> [riak\_instance\_type](#input\_riak\_instance\_type) | riak\_instance\_type | `string` | `"m5.2xlarge"` | no |
| <a name="input_riak_pri_ami_acccount_id"></a> [riak\_pri\_ami\_acccount\_id](#input\_riak\_pri\_ami\_acccount\_id) | n/a | `string` | `"176624070169"` | no |
| <a name="input_riak_qua_ami_acccount_id"></a> [riak\_qua\_ami\_acccount\_id](#input\_riak\_qua\_ami\_acccount\_id) | n/a | `string` | `"955541768397"` | no |
| <a name="input_riak_qui_ami_acccount_id"></a> [riak\_qui\_ami\_acccount\_id](#input\_riak\_qui\_ami\_acccount\_id) | n/a | `string` | `"955541768397"` | no |
| <a name="input_riak_sec_ami_acccount_id"></a> [riak\_sec\_ami\_acccount\_id](#input\_riak\_sec\_ami\_acccount\_id) | n/a | `string` | `"955541768397"` | no |
| <a name="input_riak_sen_ami_acccount_id"></a> [riak\_sen\_ami\_acccount\_id](#input\_riak\_sen\_ami\_acccount\_id) | n/a | `string` | `"955541768397"` | no |
| <a name="input_riak_tri_ami_acccount_id"></a> [riak\_tri\_ami\_acccount\_id](#input\_riak\_tri\_ami\_acccount\_id) | n/a | `string` | `"176624070169"` | no |
| <a name="input_scale_api_load_balancer_url"></a> [scale\_api\_load\_balancer\_url](#input\_scale\_api\_load\_balancer\_url) | scale\_api\_load\_balancer\_url | `string` | `"https://api.zephyrscale-stage.smartbear.com"` | no |
| <a name="input_scale_destination_cidr_block"></a> [scale\_destination\_cidr\_block](#input\_scale\_destination\_cidr\_block) | scale\_destination\_cidr\_block | `string` | `"10.0.0.0/16"` | no |
| <a name="input_scale_load_balancer_url"></a> [scale\_load\_balancer\_url](#input\_scale\_load\_balancer\_url) | scale\_load\_balancer\_url | `string` | `"https://app.tm4j-stage.smartbear.com/"` | no |
| <a name="input_scale_vpc_peering_connection_id"></a> [scale\_vpc\_peering\_connection\_id](#input\_scale\_vpc\_peering\_connection\_id) | scale\_vpc\_peering\_connection\_id | `string` | `"pcx-01ab0a786e771930b"` | no |
| <a name="input_scale_vpc_peering_private_boolean"></a> [scale\_vpc\_peering\_private\_boolean](#input\_scale\_vpc\_peering\_private\_boolean) | scale\_vpc\_peering\_private\_boolean | `bool` | `"false"` | no |
| <a name="input_secret_manager_recovery_window"></a> [secret\_manager\_recovery\_window](#input\_secret\_manager\_recovery\_window) | secret\_manager\_recovery\_window | `string` | `"0"` | no |
| <a name="input_snap_retention_days"></a> [snap\_retention\_days](#input\_snap\_retention\_days) | snap deletion period | `number` | `30` | no |
| <a name="input_squad_2_scale_ami"></a> [squad\_2\_scale\_ami](#input\_squad\_2\_scale\_ami) | n/a | `string` | `"ami-046b5b8111c19b3ac"` | no |
| <a name="input_squad_api_cluster1_load_balancer_url"></a> [squad\_api\_cluster1\_load\_balancer\_url](#input\_squad\_api\_cluster1\_load\_balancer\_url) | squad\_api\_cluster1\_load\_balancer\_url | `string` | `"https://qabench-api-pri.zephyr4jiracloud.com/"` | no |
| <a name="input_squad_api_cluster2_load_balancer_url"></a> [squad\_api\_cluster2\_load\_balancer\_url](#input\_squad\_api\_cluster2\_load\_balancer\_url) | squad\_api\_cluster2\_load\_balancer\_url | `string` | `"https://qabench-api-sec.zephyr4jiracloud.com/"` | no |
| <a name="input_squad_automation_daily"></a> [squad\_automation\_daily](#input\_squad\_automation\_daily) | squad\_automation\_daily | `bool` | `"false"` | no |
| <a name="input_squad_cluster1_load_balancer_url"></a> [squad\_cluster1\_load\_balancer\_url](#input\_squad\_cluster1\_load\_balancer\_url) | squad\_cluster1\_load\_balancer\_url | `string` | `"https://qabench-play-pri.zephyr4jiracloud.com/"` | no |
| <a name="input_squad_cluster2_load_balancer_url"></a> [squad\_cluster2\_load\_balancer\_url](#input\_squad\_cluster2\_load\_balancer\_url) | squad\_cluster2\_load\_balancer\_url | `string` | `"https://qabench-play-sec.zephyr4jiracloud.com/"` | no |
| <a name="input_tenant_service_load_balancer_url"></a> [tenant\_service\_load\_balancer\_url](#input\_tenant\_service\_load\_balancer\_url) | tenant\_service\_load\_balancer\_url | `string` | `"https://app.tm4j-dev.smartbear.com/tenant"` | no |
| <a name="input_termination_wait_time_in_minutes_cd"></a> [termination\_wait\_time\_in\_minutes\_cd](#input\_termination\_wait\_time\_in\_minutes\_cd) | termination\_wait\_time\_in\_minutes\_cd | `number` | `5` | no |
| <a name="input_vpc_cidr"></a> [vpc\_cidr](#input\_vpc\_cidr) | vpc\_cidr | `string` | `"10.2.0.0/16"` | no |
| <a name="input_xray-sec_instance_type"></a> [xray-sec\_instance\_type](#input\_xray-sec\_instance\_type) | xray-sec\_instance\_type | `string` | `"t3.medium"` | no |
| <a name="input_xray-ter_instance_type"></a> [xray-ter\_instance\_type](#input\_xray-ter\_instance\_type) | xray-ter\_instance\_type | `string` | `"t3.medium"` | no |
| <a name="input_xray_all_instance_type"></a> [xray\_all\_instance\_type](#input\_xray\_all\_instance\_type) | instance type for single xray cluster | `string` | `"t3.2xlarge"` | no |
| <a name="input_xray_count"></a> [xray\_count](#input\_xray\_count) | no of xrays required | `number` | `1` | no |
| <a name="input_xray_instance_type"></a> [xray\_instance\_type](#input\_xray\_instance\_type) | xray\_instance\_type | `string` | `"t3.medium"` | no |
| <a name="input_xray_port"></a> [xray\_port](#input\_xray\_port) | xray docker service port | `number` | `8080` | no |
| <a name="input_zquad_redis_new_enabled"></a> [zquad\_redis\_new\_enabled](#input\_zquad\_redis\_new\_enabled) | zquad\_redis\_new\_enabled | `bool` | `"false"` | no |
| <a name="input_zsquad-aws-account"></a> [zsquad-aws-account](#input\_zsquad-aws-account) | zsquad-aws-account | `string` | `"955541768397"` | no |
| <a name="input_zsquad-bastion-ami-prefix"></a> [zsquad-bastion-ami-prefix](#input\_zsquad-bastion-ami-prefix) | zsquad-bastion-ami-prefix | `string` | `"qabench-zfj-bastion"` | no |
| <a name="input_zsquad-cassandra-ami-prefix"></a> [zsquad-cassandra-ami-prefix](#input\_zsquad-cassandra-ami-prefix) | zsquad-cassandra-ami-prefix | `string` | `"qabench-zfj-cassandra"` | no |
| <a name="input_zsquad-cassandra-cluster-ami-prefix"></a> [zsquad-cassandra-cluster-ami-prefix](#input\_zsquad-cassandra-cluster-ami-prefix) | zsquad-cassandra-ami-prefix | `string` | `"qabench-zfj-cassandra-cluster"` | no |
| <a name="input_zsquad-ec2-key"></a> [zsquad-ec2-key](#input\_zsquad-ec2-key) | zsquad key | `string` | `"support-instance-key"` | no |
| <a name="input_zsquad-es-ami-prefix"></a> [zsquad-es-ami-prefix](#input\_zsquad-es-ami-prefix) | zsquad-es-ami-prefix | `string` | `"qabench-zfj-es"` | no |
| <a name="input_zsquad-es-instance-type"></a> [zsquad-es-instance-type](#input\_zsquad-es-instance-type) | zsquad-es-instance-type | `string` | `"t3.xlarge"` | no |
| <a name="input_zsquad-es-sec-ami-prefix"></a> [zsquad-es-sec-ami-prefix](#input\_zsquad-es-sec-ami-prefix) | zsquad-es-sec-ami-prefix | `string` | `"qabench-zfj-es-sec"` | no |
| <a name="input_zsquad-es-sec-instance-type"></a> [zsquad-es-sec-instance-type](#input\_zsquad-es-sec-instance-type) | zsquad-es-sec-instance-type | `string` | `"t4g.large"` | no |
| <a name="input_zsquad-es-sec-sg-name"></a> [zsquad-es-sec-sg-name](#input\_zsquad-es-sec-sg-name) | zsquad-es-sec-sg-name | `string` | `"zsquad-es-sec-sg-name"` | no |
| <a name="input_zsquad-es-sg-name"></a> [zsquad-es-sg-name](#input\_zsquad-es-sg-name) | zsquad-es-sg-name | `string` | `"zsquad-es-sg-name"` | no |
| <a name="input_zsquad-key-pair"></a> [zsquad-key-pair](#input\_zsquad-key-pair) | zsquad-key-pair | `string` | `"qabench_2022"` | no |
| <a name="input_zsquad-migrate-ami-prefix"></a> [zsquad-migrate-ami-prefix](#input\_zsquad-migrate-ami-prefix) | zsquad-migrate-ami-prefix | `list` | <pre>[<br/>  "ami-00f2869e321a915a9",<br/>  "ami-00f2869e321a915a9"<br/>]</pre> | no |
| <a name="input_zsquad-migrate-ami-prefix-env"></a> [zsquad-migrate-ami-prefix-env](#input\_zsquad-migrate-ami-prefix-env) | n/a | `string` | `"migrate"` | no |
| <a name="input_zsquad-rds-instance-snapshot-name"></a> [zsquad-rds-instance-snapshot-name](#input\_zsquad-rds-instance-snapshot-name) | zsquad-rds-instance-snapshot-name | `string` | `"qabench-zfj-rds"` | no |
| <a name="input_zsquad-redis-instance-count"></a> [zsquad-redis-instance-count](#input\_zsquad-redis-instance-count) | num\_cache\_nodes | `list` | <pre>[<br/>  "2",<br/>  "2",<br/>  "2",<br/>  "2"<br/>]</pre> | no |
| <a name="input_zsquad-redis-instance-types"></a> [zsquad-redis-instance-types](#input\_zsquad-redis-instance-types) | zsquad-redis-instance-types | `list` | <pre>[<br/>  "cache.t3.medium",<br/>  "cache.t3.medium",<br/>  "cache.t3.medium",<br/>  "cache.t4g.medium"<br/>]</pre> | no |
| <a name="input_zsquad-redis-snap-prefix"></a> [zsquad-redis-snap-prefix](#input\_zsquad-redis-snap-prefix) | zsquad-redis-snap-prefix | `list` | <pre>[<br/>  "qabench-zfj-redis-0",<br/>  "qabench-zfj-redis-1",<br/>  "qabench-zfj-redis-2",<br/>  "qabench-zfj-redis-3"<br/>]</pre> | no |
| <a name="input_zsquad-riak-ami-prefix"></a> [zsquad-riak-ami-prefix](#input\_zsquad-riak-ami-prefix) | zsquad-riak-ami-prefix | `string` | `"qabench-zfj-riak"` | no |
| <a name="input_zsquad-riak-qua-ami-prefix"></a> [zsquad-riak-qua-ami-prefix](#input\_zsquad-riak-qua-ami-prefix) | zsquad-riak-qua-ami-prefix | `string` | `"qabench-zfj-riak-qua"` | no |
| <a name="input_zsquad-riak-qui-ami-prefix"></a> [zsquad-riak-qui-ami-prefix](#input\_zsquad-riak-qui-ami-prefix) | zsquad-riak-qui-ami-prefix | `string` | `"qabench-zfj-riak-qui"` | no |
| <a name="input_zsquad-riak-sec-ami-prefix"></a> [zsquad-riak-sec-ami-prefix](#input\_zsquad-riak-sec-ami-prefix) | zsquad-riak-sec-ami-prefix | `string` | `"qabench-zfj-riak-sec"` | no |
| <a name="input_zsquad-riak-sen-ami-prefix"></a> [zsquad-riak-sen-ami-prefix](#input\_zsquad-riak-sen-ami-prefix) | zsquad-riak-sen-ami-prefix | `string` | `"qabench-zfj-riak-sen"` | no |
| <a name="input_zsquad-riak-tertiary-ami-prefix"></a> [zsquad-riak-tertiary-ami-prefix](#input\_zsquad-riak-tertiary-ami-prefix) | zsquad-riak-tertiary-ami-prefix | `string` | `"qabench-zfj-riak-tertiary"` | no |
| <a name="input_zsquad-xray-all-ami-prefix"></a> [zsquad-xray-all-ami-prefix](#input\_zsquad-xray-all-ami-prefix) | xray docker compose ami | `string` | `"qabench-zfj-xray-all"` | no |
| <a name="input_zsquad-xray-ami-prefix"></a> [zsquad-xray-ami-prefix](#input\_zsquad-xray-ami-prefix) | zsquad-xray-ami-prefix | `string` | `"qabench-zfj-xray1"` | no |
| <a name="input_zsquad-xray-sec-ami-prefix"></a> [zsquad-xray-sec-ami-prefix](#input\_zsquad-xray-sec-ami-prefix) | zsquad-xray-ami-prefix | `string` | `"qabench-zfj-xray2"` | no |
| <a name="input_zsquad-xray-ter-ami-prefix"></a> [zsquad-xray-ter-ami-prefix](#input\_zsquad-xray-ter-ami-prefix) | zsquad-xray-ami-prefix | `string` | `"qabench-zfj-xray3"` | no |
| <a name="input_zsquad_acm_cert_arn"></a> [zsquad\_acm\_cert\_arn](#input\_zsquad\_acm\_cert\_arn) | zsquad\_acm\_cert\_arn | `string` | `"arn:aws:acm:us-west-2:955541768397:certificate/d5e942e5-dae4-4679-a591-97f112f1d57c"` | no |
| <a name="input_zsquad_codedeploy_service_role_arn"></a> [zsquad\_codedeploy\_service\_role\_arn](#input\_zsquad\_codedeploy\_service\_role\_arn) | zsquad\_codedeploy\_service\_role\_arn | `string` | `"arn:aws:iam::955541768397:role/ZFJ-CODEDEPLOY-ROLE"` | no |
| <a name="input_zsquad_redis_elasticache_redis_jcma_enabled"></a> [zsquad\_redis\_elasticache\_redis\_jcma\_enabled](#input\_zsquad\_redis\_elasticache\_redis\_jcma\_enabled) | zsquad\_redis\_elasticache\_redis\_jcma\_enabled | `bool` | `"false"` | no |
| <a name="input_zsquad_redis_multi_az_enabled"></a> [zsquad\_redis\_multi\_az\_enabled](#input\_zsquad\_redis\_multi\_az\_enabled) | zsquad\_redis\_multi\_az\_enabled | `list` | <pre>[<br/>  "false",<br/>  "false",<br/>  "false",<br/>  "false"<br/>]</pre> | no |
| <a name="input_zsquad_redis_port"></a> [zsquad\_redis\_port](#input\_zsquad\_redis\_port) | zsquad-redis-port | `list` | <pre>[<br/>  "7100",<br/>  "7100",<br/>  "7100",<br/>  "7100"<br/>]</pre> | no |
| <a name="input_zsquad_ui_acm_cert_arn"></a> [zsquad\_ui\_acm\_cert\_arn](#input\_zsquad\_ui\_acm\_cert\_arn) | zsquad\_ui\_acm\_cert\_arn | `string` | `"arn:aws:acm:us-east-1:955541768397:certificate/7521b329-eacb-4989-a76e-8aa4c6689ab1"` | no |

## Outputs

No outputs.
