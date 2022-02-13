* users
   * nickname： string
   * email： string
   * password_digest： string
   * admin： boolean
   * created_at： datetime
   * updated_at： datetime

* questions
   * user_id： integer
   * title： string
   * body： text
   * solved: boolean
   * created_at： datetime
   * updated_at： datetime

* answers
   * user_id： integer
   * question_id： integer
   * body： text
   * created_at： datetime
   * updated_at： datetime

* active_storage_blobs
   * key: string
   * filename: string
   * content_type: string
   * metadata: text
   * service_name: string
   * byte_size: bigint
   * checksum: string
   * created_at: datetime


* active_storage_attachments
   * name: string
   * record_type: string
   * record_id: integer
   * blob_id: integer
   * blob: references
   * created_at: datetime

* active_storage_variant_records
   * blob_id: integer
   * variation_digest: string

