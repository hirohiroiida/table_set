* users
   * nickname： string
   * avatar_image_id： string
   * email： string
   * password： string
   * hostman： boolean
   * created_at： datetime
   * updated_at： datetime

* questions
   * user_id： integer
   * title： string
   * body： text
   * created_at： datetime
   * updated_at： datetime

* answers
   * user_id： integer
   * question_id： integer
   * comment： text
   * created_at： datetime
   * updated_at： datetime

* solutions
   * user_id： integer
   * questions_id： integer
   * created_at： datetime
   * updated_at： datetime





