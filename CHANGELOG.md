## Next Release

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
