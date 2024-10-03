## Next Release

### Agorapulse AWS SDK 3.3.0

## What's Changed
* DynamoDb Converters v2 Improvements by @musketyr in https://github.com/agorapulse/micronaut-aws-sdk/pull/263
  * automatic replacing empty string sets with `null`
  * new `@ConvertedJson` annotation as a successor of `DynamoDBTypeConvertedJson`


**Full Changelog**: https://github.com/agorapulse/micronaut-aws-sdk/compare/3.2.0...3.3.0

### Micronaut Facebook SDK 1.0.2

## What's Changed
* Migrated to Micronaut 4.x by @musketyr in https://github.com/agorapulse/micronaut-facebook-sdk/pull/14
* Upgrade Kordamp to 0.54.0 by @musketyr in https://github.com/agorapulse/micronaut-facebook-sdk/pull/15


**Full Changelog**: https://github.com/agorapulse/micronaut-facebook-sdk/compare/0.6.0...1.0.2

### Agorapulse AWS SDK 2.1.12-micronaut-1.0

* ability to encode multipart email body using base64

### Agorapulse AWS SDK 3.0.2

* added ability to specify using `base64` encoding for multipart emails

### Micronaut Worker 2.0.1

* test release after re-enabling BOM synchronization, no code change

### Micronaut Worker 2.0.0

* **Breaking Change** Migrated to Micronaut 4.x

### Micronaut Log4AWS 4.0.0

* Upgraded to Micronaut 4.x and Java 17

### Micronaut Slack 2.0.0

**Breaking change** Migrated to Micronaut 4.x and Java 17

### Agorapulse AWS SDK 3.0.1

* repeated release due previous publishing exception

### Agorapulse AWS SDK 3.0.0

**Breaking change** Migrated to Micronaut 4.x

### Micronaut Newrelic Library 2.0.0

**Breaking Change** Upgrade to Micronaut 4.x

### Micronaut Snitch 2.0.0

**Breaking Change** Upgrade to Micronaut 4.x

### Micronaut Segment Library 2.0.0-micronaut-1.0

*Breaking Change Migrated to Micronaut 4.x

### Micronaut Rethrow 2.0.0

**Breaking Change** Upgrade to Micronaut 4.x

### Micronaut Permissions 2.0.0

* upgraded to Micronaut 4.x

### Micronaut Permissions 1.2.0-micronaut-1.0

* ability to grant privileges for any object (useful with `@ResultRequiresPermissions`)

### HTTP Interactions Test Framework 2.0.4

* fixed situation when Micronaut HTTP client wasn't on the classpath

### HTTP Interactions Test Framework 2.0.3

* fixed Micronaut HTTP client headers not being propagated

### HTTP Interactions Test Framework 2.0.2

* fixed Micronaut HTTP client error handling

### Groovy REST Unit Test Framework 2.0.1

* made Micronaut dependencies compile only

### Groovy REST Unit Test Framework 2.0.0


## Breaking Changes

* The minimal Java version has been set to Java 11
* The Micronaut module has been upgraded to Micronaut 4.x, Groovy 4.x and Java 17
* The HTTP module has been removed as the `Http` client is now part of the core `gru` package
* The original HTTP module has been renamed to `gru-okhttp` and the client accordingly to `OkHttp`
* The libraries required to evaluate HTML responses has been moved to compile only dependencies
* Micronaut module now uses `micronaut-http-client` instead of the default HTTP one


## New Features

* Small improvements in the Kotlin DSL
* No need to specify the reference class when calling `Gru.create()` or `Http.create()`. The class is automatically detected using the stack walker API.

### Micronaut Newrelic Library 1.2.3-micronaut-1.0

## What's Changed
* Add authentication on service client by @DKarim in https://github.com/agorapulse/micronaut-newrelic/pull/29

## New Contributors
* @DKarim made their first contribution in https://github.com/agorapulse/micronaut-newrelic/pull/29

**Full Changelog**: https://github.com/agorapulse/micronaut-newrelic/compare/1.2.2...1.2.3

### Micronaut Grails 3.3.0-micronaut-1.0

* reworked `MicronautGrailsAppServletInitializer` to match the latest from the Grails codebase

### Micronaut Grails 3.2.0-micronaut-1.0

* minimal Grails 5.x compatibility by setting the `setAllowCircularReferences(true)` if the method exists

### Groovy REST Unit Test Framework 1.4.0

* upgraded build to Gradle 7.x
* upgraded Kotlin to 1.8.x
* upgraded Micronaut to 3.x
* upgraded Grails to 5.x

### Agorapulse AWS SDK 2.1.11-micronaut-1.0

* ability to disable kinesis listeners

### Agorapulse AWS SDK 2.1.10-micronaut-1.0

## What's Changed
* Allow adding configuration set on emails for SDK v2 by @DKarim in https://github.com/agorapulse/micronaut-aws-sdk/pull/178


**Full Changelog**: https://github.com/agorapulse/micronaut-aws-sdk/compare/2.1.8...2.1.10

### Agorapulse AWS SDK 2.1.9-micronaut-1.0

## What's Changed
* Allow adding configuration set on emails by @DKarim in https://github.com/agorapulse/micronaut-aws-sdk/pull/175


**Full Changelog**: https://github.com/agorapulse/micronaut-aws-sdk/compare/2.1.7...2.1.9

### Agorapulse AWS SDK 2.1.7-micronaut-1.0

## What's Changed
* Allow adding tags on emails by @DKarim in https://github.com/agorapulse/micronaut-aws-sdk/pull/172


**Full Changelog**: https://github.com/agorapulse/micronaut-aws-sdk/compare/2.1.6...2.1.7

### Micronaut Log4AWS 3.0.0-micronaut-1.0

* enforcing versions from Micronaut BOM that forces Slf4j 1.7.x
* using `log4j-slf4j-impl` instead of `log4j-slf4j18-impl` because of the change above

### Agorapulse AWS SDK 2.1.6-micronaut-1.0

* ability to specify tags for newly created queues

### Micronaut Worker 1.3.0-micronaut-1.0

* default waiting time set to `20s` (only applicable for SQS queues)

### Amazon Web Services SDK Grails Plugin 2.4.16

* use pay per request for DynamoDB tables by @musketyr in https://github.com/agorapulse/grails-aws-sdk/pull/127

### Micronaut Permissions 1.1.1-micronaut-1.0

- Add inherited annotation to ResultRequiresPermission annotation to use it on interfaces.

### Groovy REST Unit Test Framework 1.3.1

## What's Changed
* Fix checking headers and cookies in response from redirection by @wololock in https://github.com/agorapulse/gru/pull/82

## New Contributors
* @wololock made their first contribution in https://github.com/agorapulse/gru/pull/82

**Full Changelog**: https://github.com/agorapulse/gru/compare/1.3.0...1.3.1

### Micronaut Permissions 1.1.0-micronaut-1.0

- Add annotation to check permission on result

### Agorapulse AWS SDK 2.1.5-micronaut-1.0

## What's Changed
* force path style for itegration tests by @musketyr in https://github.com/agorapulse/micronaut-aws-sdk/pull/161
* prevent hyphening keys in the localstack.env.* configuration map by @wololock in https://github.com/agorapulse/micronaut-aws-sdk/pull/162


**Full Changelog**: https://github.com/agorapulse/micronaut-aws-sdk/compare/2.1.4...2.1.5

### Groovy REST Unit Test Framework 1.3.0

- ability to retrieve the response text
- automatic closing of Gru instance after the feature method in Spock

### Micronaut Permissions 1.0.5-micronaut-1.0

- fixed cast of `Map` to an `Iterable`

### Micronaut Log4AWS 2.1.0-micronaut-1.0



### Micronaut Permissions 1.0.4-micronaut-1.0

- allow null iterable

### Micronaut Permissions 1.0.3-micronaut-1.0

- verify all method arguments

### Micronaut Facebook SDK 0.6.0-micronaut-1.0

- Updates the restfb to the latest 2023.3.0

### Agorapulse AWS SDK 2.1.4-micronaut-1.0

- Allow path style URLs for S3

### Agorapulse AWS SDK 2.1.3-micronaut-1.0

- Retry release after Sonatype publishing issue

### Agorapulse AWS SDK 2.1.1-micronaut-1.0

- Add support for SNS Fifo topics

### Agorapulse AWS SDK 2.1.0-micronaut-1.0

- Move DynamoDB DAX to its own library

### Micronaut Worker 1.2.6-micronaut-1.0

* do not throw exception from method processor

### Micronaut Worker 1.2.5-micronaut-1.0

* replaced `ConversionService`  with `Environment` as workaround to https://github.com/micronaut-projects/micronaut-core/issues/7948

### Agorapulse AWS SDK 2.0.10-micronaut-1.0

* ability to specify container for integration testing

### Micronaut Facebook SDK 0.5.3-micornaut-1.0

* fixed configuration 

### Micronaut Newrelic Library 1.2.2-micronaut-1.0

* use explicit `@Nullable` for configuration properties

### Micronaut Newrelic Library 1.2.1-micronaut-1.0

* NewRelic token must be set to instantiate the filter
* Filter must be instantiated to instantiate the HTTP clients

### Micronaut Newrelic Library 1.2.0-micronaut-1.0

* new (preferred) declarative service client

### Micronaut Worker 1.2.4-micronaut-1.0



### Micronaut Worker 1.2.3-micronaut-1.0

* adde Micronaut Worker Management library to expose `/jobs` endpoint

### Agorapulse AWS SDK 2.0.9-micronaut-1.0

* upgraded default Localstack container to `1.3.0`

### Agorapulse AWS SDK 2.0.8-micronaut-1.0

* set timeout for `@LambdaClient` clients
* CloudWatch Logs integration

### Agorapulse AWS SDK 2.0.7-micronaut-1.0

* ability to define env variables for integration Localstack container

### Agorapulse AWS SDK 2.0.6-micronaut-1.0

* Lambda Client: throw exception when function error is returned

### Micronaut Grails 3.1.3-micronaut-1.0

* fixed converting of properties to map with multiple values (e.g. sql settings)

### Micronaut Slack 1.0.4-micronaut-1.0

* automatic event's duplicate filtering

### Agorapulse AWS SDK 2.0.5-micronaut-1.0

* Added container credentials provider into the default chain #119 

### Groovy REST Unit Test Framework 1.2.5

* fixed closure parameters definition for Groovy extensions

### Micronaut Slack 1.0.3-micronaut-1.0

* do not set empty bot token
* fixed test dependencies wrong configuration

### Micronaut Slack 1.0.2-micronaut-1.0

* S3 support

### Micronaut Slack 1.0.1-micronaut-1.0

* documentation fix - no code change

### Micronaut Worker 1.2.2-micronaut-1.0

* moved job logging to debug
* SQS v2 support

### Agorapulse AWS SDK 2.0.4-micronaut-1.0

* co-release to internal repository

### Agorapulse AWS SDK 2.0.3-micronaut-1.0

* Lambda client support
* Fixed table name for Kinesis Worker

### Groovy REST Unit Test Framework 1.2.4

* automatic extended timeouts for debug sessions

### Micronaut Snitch 1.2.1-micronaut-1.0

* fixed documentation publishing

### Agorapulse AWS SDK 2.0.2-micronaut-1.0

* fixed `Map` properties in DynamoDB v2 entities #111 

### Groovy REST Unit Test Framework 1.2.3

* support for reusing existing `RequestStreamingHandler` in `ApiGatewayProxy` integration

### Amazon Web Services SDK Grails Plugin 2.4.15

* added missing `@Slf4j` annotation for the Kinesis `AbstractClientService` 

### Micronaut Log4AWS 2.0.9-micronaut-1.0

* longer timeout for sentry flush

### Micronaut Newrelic Library 1.1.3-micronaut-1.0

* support for unsafe calls

### Micronaut Log4AWS 2.0.8-micronaut-1.0

BREAKING CHANGE: removed the `Logging*` interface as they fails when deployed

### Micronaut Log4AWS 2.0.7-micronaut-1.0

* helper classes and interfaces to ensure logging 

### Groovy REST Unit Test Framework 1.2.2

* support for header matchers #72 thanks to @driverpt 

### Agorapulse AWS SDK 2.0.1-micronaut-1.0

* fixed repeated initialization of metadata table in the cache

### Groovy REST Unit Test Framework 1.2.1

* fixed error for integration tests without web app (#71 thanks to @driverpt)

### Groovy REST Unit Test Framework 1.2.0

* calling `close` on the `Gru` instance does not reset configurations which allows reusing the instance in DI containers such as Spring or Micronaut (fixes #68)

### Micronaut Facebook SDK 0.5.2-micornaut-1.0

* introduced BOM

### Groovy REST Unit Test Framework 1.1.2

* Gru BOM (#64)
* Gru Kotlin (#55)

### Agorapulse AWS SDK 2.0.0-micronaut-1.0

* new Kotlin DSL for DynamoDB v2
* ability to use reactive implementation from the supported ones for DynamoDB declarative services
* mirroring the DynamoDB v2 annotations which can be also used on fields
* fixed writing DynamoDB v2 entities using Groovy 3.x

### BREAKING CHANGE
* removed all references to `io.reactivex.Flowable` from the API in favor of `org.reactivestreams.Publisher`


### Micronaut Log4AWS 2.0.6-micronaut-1.0

* `TagHelper` class to handle MDC
* use MDC based filter with setting `sentry.filter.type` to `mdc`
* use reactive-based filter with setting `sentry.filter.type` to `reactive`

### Micronaut Worker 1.2.1-micronaut-1.0

* new helper methods in the `JobManager` class

### Groovy REST Unit Test Framework 1.1.1

* throwing explanatory exception for Groovy issue with `get` method

### Groovy REST Unit Test Framework 1.1.0

* BREAKING CHANGE: test methods for HTTP verbs no accepts only `String` not `CharSequence`
* Automatic language reference for IntelliJ

### Agorapulse AWS SDK 1.7.3-micronaut-1.0

* support for incremental annotation processing

### Micronaut Permissions 1.0.2-micronaut-1.0

* made the annotations inherited

### Groovy REST Unit Test Framework 1.0.4

ability to specify delegate for the Micronaut client

### Micronaut Log4AWS 2.0.5-micronaut-1.0

* another way to handle sentry scopes

### Micronaut Log4AWS 2.0.4-micronaut-1.0

* simplified sentry filter scope handling

### Agorapulse AWS SDK 1.7.2-micronaut-1.0

* adopted new Gradle configurations (some dependencies moved to runtime)
* Automatic Localstack integration

### Groovy REST Unit Test Framework 1.0.3

* upgraded JSoup as the previous version contains security issues

### Groovy REST Unit Test Framework 1.0.2

* allow more digits in ISO date fraction part (fixes ISO date matchers on Java 11)

### Groovy REST Unit Test Framework 1.0.1

* re-release due previous publishing failure

### Micronaut Log4AWS 2.0.3-micronaut-1.0

* fixed scope not popped when error happened

### Agorapulse AWS SDK 1.6.2-micronaut-1.0

* bumped AWS libraries versions
* Compressed DynamoDB Field Converter

### Micronaut Newrelic Library 1.1.2-micronaut-1.0

* preventing _Recursive update_ issues when evaluating the bean conditions

### Micronaut Log4AWS 2.0.2-micronaut-1.0

* support for legacy `SENTRY_DSN ` definition

### Micronaut Log4AWS 2.0.1-micronaut-1.0

* execute `Sentry.flush()` from `@LogError` calls

### Micronaut Permissions 1.0.1-micronaut-1.0



### Micronaut Log4AWS 2.0.0-micronaut-1.0

## Breaking Change

* switched to Sentry 5.4.0

### Micronaut Permissions 1.0.0-micronaut-1.0

* initial release

### Micronaut Rethrow 1.1.1-micronaut-1.0

* move `Rethrow` around the `Retryable` annotations

### Micronaut Grails 3.1.2-micronaut-1.0

* fixed Spring 2.1.x compatibility

### Micronaut Grails 3.1.1-micronaut-1.0

* fixed issue with older Spring Boot versions

### Micronaut Worker 1.2.0-micronaut-1.0

* support for multiple Micronaut versions

### Micronaut Segment Library 1.1.0-micronaut-1.0

* support for multiple Micronaut versions

### Micronaut Rethrow 1.1.0-micronaut-1.0

* support for multiple Micronaut versions

### Micronaut Recurly 1.1.2-micronaut-1.0

* yet another fix for releasing the guide

### Micronaut Newrelic Library 1.1.1-micronaut-1.0

* fixed MN 3.x release

### Micronaut Grails 3.1.0-micronaut-1.0

* support for a multiple versions of Micronaut
  * MN 2.x and MN 3.x are evaluated against Grails 5.1.x

### Agorapulse AWS SDK 1.6.1-micronaut-1.0

* fixed release for MN 3.x version

### Micronaut Facebook SDK 0.5.1

* re-release with multiple Micronaut versions

### Micronaut Log4AWS 1.2.6-micronaut-1.0

Upgrade lo4j to 2.17.1

### Micronaut Log4AWS 1.2.5-micronaut-1.0

* Upgraded to Log4J 2.17.0

### Groovy REST Unit Test Framework 0.9.5

* ability to specify more acceptable statuses
* more statuses allowed for redirection

### Micronaut Log4AWS 1.2.4-micronaut-1.0

* Upgraded to Log4J 2.16.0

### Micronaut Log4AWS 1.2.3-micronaut-1.0

* explicit Log4J dependencies and BOM

### Agorapulse Testing Libraries 0.2.3

* [Fixt] Copy whole testing directory

### Micronaut Worker 1.1.4

* Redis queues

### Micronaut Worker 1.1.3

* disabled in CLI by default
* increased the number of consumed messages from SQS queue to 10

### Micronaut Snitch 1.1.3

* **BREAKING CHANGE** - no-op service issues warning if snitch  is not configured

### Micronaut Rethrow 1.0.1

* removed configuration files which may override the configuration files from the application

### Micronaut Worker 1.1.2

* backward compatibility with the simple format of the messages which might pending in the queues

### Groovy Unit Testing 0.9.4

* upgraded Fixt

### Groovy Unit Testing 0.9.3

* Fixed Micronaut file upload

### Agorapulse Testing Libraries 0.2.2

* [Fixt] Return the newly create file for `writeText` and `writeStream`

### Micronaut Grails 3.0.7

* BREAKING CHANGE - enums are no longer generated by default by the JPA generator

### Micronaut Grails 3.0.6

* BREAKING CHANGE in GORM to Micronaut generator - entities are generated into package with suffix

### Micronaut Grails 3.0.5

* support for generating Micronaut Data JDBC repositories

### Micronaut Grails 3.0.4

 * GORM to JPA generator
 * Integration tests support for `MicronautGrailsApp`

### Micronaut Segment Library 1.0.4.1

* fixed Segment logging format

### Micronaut Segment Library 1.0.4

* added logging using Slf4j
* beans for callbacks, network executor, thread factory, retrofit client
* attempt to make calls on functions blocking

### Micronaut Segment Library 1.0.3

* downgrade Segment library to 2.x

### Micronaut Segment Library 1.0.1

* back to using factory to instantiate either real service or loop

### Micronaut Segment Library 1.0.0

* Ability to add integration options
* Better Java support using builder consumers
* Better Groovy support with builders


### Micronaut Newrelic Library 1.0.9

* ensure fallback service is override

### Micronaut Newrelic Library 1.0.8

* ability to use HTTP implementation even the NewRelic libraries are on the class path

### Micronaut Worker 1.1.1

* ablity to set default queue type (e.g. `local` for local environment)

### Amazon Web Services SDK Grails Plugin 2.4.14

* reverted using static credentials once obtained (fixed expired credentials issue) 

### Groovy Code Checks 0.9.1

* ignore code within `*DataService` classes
* bug fix

### Amazon Web Services SDK Grails Plugin 2.4.13

* re-release (missing deployer password before)

###  0.9.0

* Initial port of the GORM checker

### Micronaut Worker 1.1.0

* disable jobs by default in tests and for functions

### Amazon Web Services SDK Grails Plugin 2.4.12

* fixed too many errors when the credentials are not configured

## 2021.5.17.0744
