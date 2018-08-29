---
name: AWS Simple Queue Service
x-slug: aws-simple-queue-service
description: Amazon Simple Queue Service (SQS) is a fast, reliable, scalable, fully
  managed message queuing service. Amazon SQS makes it simple and cost-effective to
  decouple the components of a cloud application. You can use Amazon SQS to transmit
  any volume of data, without losing messages or requiring other services to be always
  available. Amazon SQS includesstandard queueswith high throughput and at-least-once
  processing, andFIFO queuesthat provide FIFO (first-in, first-out) delivery and exactly-once
  processing. With Amazon SQS, you can offload the administrative burden of operating
  and scaling a highly available messaging cluster, while paying a low price for only
  what you use.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Simple Queue Service
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Simple Queue Service API - Add Permission
  x-api-slug: actionaddpermission-get
  description: Adds a permission to a queue for a specific.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionaddpermission-get-openapi.md
- name: AWS Simple Queue Service API - Change Message Visibility
  x-api-slug: actionchangemessagevisibility-get
  description: Changes the visibility timeout of a specified message in a queue to
    a new value.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionchangemessagevisibility-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionchangemessagevisibility-get-openapi.md
- name: AWS Simple Queue Service API - Change Message Visibility Batch
  x-api-slug: actionchangemessagevisibilitybatch-get
  description: Changes the visibility timeout of multiple messages.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionchangemessagevisibilitybatch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionchangemessagevisibilitybatch-get-openapi.md
- name: AWS Simple Queue Service API - Create Queue
  x-api-slug: actioncreatequeue-get
  description: Creates a new standard or FIFO queue or returns the URL of an existing
    queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actioncreatequeue-get-openapi.md
- name: AWS Simple Queue Service API - Delete Message
  x-api-slug: actiondeletemessage-get
  description: Deletes the specified message from the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actiondeletemessage-get-openapi.md
- name: AWS Simple Queue Service API - Delete Message Batch
  x-api-slug: actiondeletemessagebatch-get
  description: Deletes up to ten messages from the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actiondeletemessagebatch-get-openapi.md
- name: AWS Simple Queue Service API - Delete Queue
  x-api-slug: actiondeletequeue-get
  description: Deletes the queue specified by the QueueUrl, even if the queue is empty.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actiondeletequeue-get-openapi.md
- name: AWS Simple Queue Service API - Get Queue Attributes
  x-api-slug: actiongetqueueattributes-get
  description: Gets attributes for the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actiongetqueueattributes-get-openapi.md
- name: AWS Simple Queue Service API - Get Queue Url
  x-api-slug: actiongetqueueurl-get
  description: Returns the URL of an existing queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actiongetqueueurl-get-openapi.md
- name: AWS Simple Queue Service API - List Dead Letter Source Queues
  x-api-slug: actionlistdeadlettersourcequeues-get
  description: Returns a list of your queues that have the RedrivePolicy queue attribute
    configured with a dead letter queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionlistdeadlettersourcequeues-get-openapi.md
- name: AWS Simple Queue Service API - List Queues
  x-api-slug: actionlistqueues-get
  description: Returns a list of your queues.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionlistqueues-get-openapi.md
- name: AWS Simple Queue Service API - Purge Queue
  x-api-slug: actionpurgequeue-get
  description: Deletes the messages in a queue specified by the QueueURL parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionpurgequeue-get-openapi.md
- name: AWS Simple Queue Service API - Receive Message
  x-api-slug: actionreceivemessage-get
  description: Retrieves one or more messages (up to 10), from the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionreceivemessage-get-openapi.md
- name: AWS Simple Queue Service API - Remove Permission
  x-api-slug: actionremovepermission-get
  description: Revokes any permissions in the queue policy that matches the specified
    Label parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionremovepermission-get-openapi.md
- name: AWS Simple Queue Service API - Send Message
  x-api-slug: actionsendmessage-get
  description: Delivers a message to the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionsendmessage-get-openapi.md
- name: AWS Simple Queue Service API - Send Message Batch
  x-api-slug: actionsendmessagebatch-get
  description: Delivers up to ten messages to the specified queue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionsendmessagebatch-get-openapi.md
- name: AWS Simple Queue Service API - Set Queue Attributes
  x-api-slug: actionsetqueueattributes-get
  description: Sets the value of one or more queue attributes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonSQS.png
  humanURL: https://aws.amazon.com/sqs/
  baseURL: :///
  tags: Amazon Web Services, Jobs, Orchestration, Stack Network, API Service Provider,
    API Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-simple-queue-service/master/_listings/aws-simple-queue-service/actionsetqueueattributes-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.simple.notification.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.simple.queue.service.stack.network
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/Amazon-SQ
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/sqs/index.html
- type: x-console
  url: https://console.aws.amazon.com/sqs/
- type: x-documentation
  url: http://docs.aws.amazon.com/AWSSimpleQueueService/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/sqs/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=12
- type: x-getting-started
  url: https://aws.amazon.com/sqs/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/sqs/pricing/
- type: x-website
  url: https://aws.amazon.com/sqs/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---