# Using Google Cloud Storage (GCS) with the S3 SDK

[Google Cloud Storage][1] features APIs that allows developers to store and access arbitrarily-large
objects. The [GCS XML API][5] provides support for AWS S3 API users that use S3 SDKs.
Learn more about [Migrating to GCS][6].

## Prerequisites

Install [Maven](http://maven.apache.org/).

## Setup

1. Clone this repo.

   ```
   git clone https://github.com/GoogleCloudPlatform/java-docs-samples.git
   ```

1. Change into this directory:

   ```
   cd java-docs-samples/storage/s3-sdk
   ```

1. Build this project from this directory:

   ```
   mvn package
   ```

1. Get your [Interoperable Storage Access Keys][3] and set the following environment variables:

   * AWS_ACCESS_KEY_ID=[ACCESS_KEY]
   * AWS_SECRET_ACCESS_KEY=[SECRET]


## List GCS buckets using the AWS S3 SDK

1. Run example using the following Maven command:

   ```
   mvn exec:java -Dexec.mainClass=S3Sdk
   ```

## Products
- [Google Cloud Storage][2]

## Language
- [Java][2]

## Dependencies
- [AWS S3 Java SDK][4]

[1]: https://cloud.google.com/storage
[2]: https://java.com
[3]: https://cloud.google.com/storage/docs/migrating#keys
[4]: https://mvnrepository.com/artifact/com.amazonaws/aws-java-sdk-s3
[5]: https://cloud.google.com/storage/docs/xml-api/overview
[6]: https://cloud.google.com/storage/docs/migrating