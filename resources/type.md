Google Cloud Platform (GCP) has a broad range of resource types, which represent components you can create, configure, and manage within the platform. Here’s a categorized list of the major GCP resource types:


🧠 1. Identity & Access Management
  - google_project
  -	google_service_account
  -	google_iam_policy
  - google_iam_role
  - google_iam_binding
  - google_iam_member
  - google_folder
  - google_organization

🖥️ 2. Compute Resources
  - google_compute_instance (VM)
  - google_compute_instance_template
  - google_compute_instance_group
  - google_compute_autoscaler
  - google_compute_disk
  - google_compute_snapshot
  - google_compute_image
  - google_compute_region_instance_group_manager

☁️ 3. Serverless & Containers
  - google_cloudfunctions_function
  - google_cloud_run_service
  - google_app_engine_application
  - google_app_engine_service
  - google_container_cluster (GKE)
  - google_container_node_pool

🗃️ 4. Storage & Databases
  - google_storage_bucket
  - google_storage_object
  - google_sql_database_instance
  - google_sql_user
  - google_sql_database
  - google_spanner_instance
  - google_spanner_database
  - google_firestore_database
  - google_bigtable_instance
  - google_bigtable_table
  - google_bigquery_dataset
  - google_bigquery_table

🌐 5. Networking
  - google_compute_network (VPC)
  - google_compute_subnetwork
  - google_compute_firewall
  - google_compute_router
  - google_compute_vpn_gateway
  - google_compute_forwarding_rule
  - google_compute_address (Static IP)
  - google_compute_global_address
  - google_compute_lb_backend_service
  - google_compute_target_http_proxy
  - google_compute_target_https_proxy
  - google_compute_ssl_certificate

🔐 6. Security & Identity
  - google_kms_key_ring
  - google_kms_crypto_key
  - google_secret_manager_secret
  - google_secret_manager_secret_version
  - google_access_context_manager_access_policy
  - google_access_context_manager_access_level

📈 7. Monitoring, Logging & Ops
  - google_logging_project_sink
  - google_logging_metric
  - google_monitoring_alert_policy
  - google_monitoring_dashboard
  - google_monitoring_notification_channel
  - google_monitoring_uptime_check_config

📡 8. APIs, Endpoints & DNS
  - google_project_service (Enable APIs)
  - google_endpoints_service
  - google_dns_managed_zone
  - google_dns_record_set

🤖 9. AI/ML & Data Services
  - google_ai_platform_model
  - google_ai_platform_job
  - google_vertex_ai_endpoint
  - google_vertex_ai_model

🧪 10. Dev Tools & CI/CD
  - google_cloudbuild_trigger
  - google_sourcerepo_repository
  - google_artifact_registry_repository

🔄 11. Migration & Transfer
  - google_storage_transfer_job
  - google_storage_bucket_object
  - google_data_transfer_config (BigQuery Data Transfer)

🗂️ 12. Resource Management
  - google_project_iam_binding
  - google_folder_iam_binding
  - google_organization_iam_binding
  - google_project_service_identity
