# EPAM Report Portal Continuous Delivery Dashboard

| COMPONENT                                                                             | COMPILE | UNIT TEST (COVERAGE) | STATIC ANALYSIS | PACKAGE SOFTWARE | BUILD ENV | CREATE DB | DEPLOY | RUN ACCEPTANCE TESTS | LOAD TESTING | PERF TESTING | RELEASE |
| ---                                                                                   | ---     | ---       | ---             | ---              | ---       | ---       | ---    | ---                  | ---          | ---          | ---     | 
| [Services](https://github.com/reportportal?utf8=%E2%9C%93&q=service-) ||||||||||||
| [`Redis`](https://github.com/reportportal/service-registry)                           | [![Build Status](https://travis-ci.org/reportportal/service-registry.svg?branch=master)](https://travis-ci.org/reportportal/service-gateway)      | TBD        | TBD              | [ ![Download](https://api.bintray.com/packages/epam/reportportal/service-registry/images/download.svg) ](https://bintray.com/epam/reportportal/service-registry/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Authorization Service`](https://github.com/reportportal/service-authorization)      | [![Build Status](https://travis-ci.org/reportportal/service-authorization.svg?branch=master)](https://travis-ci.org/reportportal/service-authorization) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Gateway Service`](https://github.com/reportportal/service-gateway)                  | [![Build Status](https://travis-ci.org/reportportal/service-gateway.svg?branch=master)](https://travis-ci.org/reportportal/service-gateway) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`API Service`](https://github.com/reportportal/service-api)                          | [![Build Status](https://travis-ci.org/reportportal/service-api.svg?branch=master)](https://travis-ci.org/reportportal/service-api) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`UI Service`](https://github.com/reportportal/service-ui)                            | [![Build Status](https://travis-ci.org/reportportal/service-ui.svg?branch=master)](https://travis-ci.org/reportportal/service-ui) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`JIRA Service`](https://github.com/reportportal/service-jira)                        | [![Build Status](https://travis-ci.org/reportportal/service-jira.svg?branch=master)](https://travis-ci.org/reportportal/service-jira) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Rally Service`](https://github.com/reportportal/service-rally)                      | [![Build Status](https://travis-ci.org/reportportal/service-rally.svg?branch=master)](https://travis-ci.org/reportportal/service-rally) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [Clients - API integrations](https://github.com/reportportal?utf8=%E2%9C%93&q=agent-) ||||||||||||
| [`Python client`](https://github.com/reportportal/client-Python)                      | NO       | TBD        | TBD              | [![PyPI](https://img.shields.io/pypi/v/reportportal-client.svg?maxAge=2592000)](https://pypi.python.org/pypi/reportportal-client) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Java http client`](https://github.com/reportportal/client-java-httpclient-repacked) | NO       | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Java rest client`](https://github.com/reportportal/client-java-rest-core)           | [![Build Status](https://travis-ci.org/reportportal/client-java-rest-core.svg?branch=master)](https://travis-ci.org/reportportal/client-java-rest-core) | TBD        | TBD              | [![Download](https://api.bintray.com/packages/epam/reportportal/rest-client-core/images/download.svg)](https://bintray.com/epam/reportportal/rest-client-core/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Java core client`](https://github.com/reportportal/client-java-core)                | [![Build Status](https://travis-ci.org/reportportal/client-java-core.svg?branch=master)](https://travis-ci.org/reportportal/client-java-core) | TBD        | TBD              | [![Download](https://api.bintray.com/packages/epam/reportportal/client-java-core/images/download.svg) ](https://bintray.com/epam/reportportal/client-java-core/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`.NET client`](https://github.com/reportportal/client-net)                           | [![Build status](https://ci.appveyor.com/api/projects/status/thjw94949tm5lbw5?svg=true)](https://ci.appveyor.com/project/nvborisenko/client-net) | TBD        | TBD              | [![NuGet version](https://badge.fury.io/nu/reportportal.client.svg)](https://badge.fury.io/nu/reportportal.client) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`JavaScript client`](https://github.com/reportportal/client-javascript)              | NO       | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [Agents - Frameworks integration](https://github.com/reportportal?utf8=%E2%9C%93&q=agent-) ||||||||||||
| [`TestNG agent`](https://github.com/reportportal/agent-java-testNG)                   | [![Build Status](https://travis-ci.org/reportportal/agent-java-testNG.svg?branch=master)](https://travis-ci.org/reportportal/agent-java-testNG)| TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Robot Framework agent`](https://github.com/reportportal/agent-Python-RobotFramework) | [![Build Status](https://travis-ci.org/reportportal/agent-Python-RobotFramework.svg?branch=master)](https://travis-ci.org/reportportal/agent-Python-RobotFramework) | TBD        | TBD              | [![PyPI](https://img.shields.io/pypi/v/robotframework-reportportal.svg?maxAge=2592000)](https://pypi.python.org/pypi/robotframework-reportportal) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Ruby agent`](https://github.com/reportportal/agent-ruby)                            | [![Build Status](https://travis-ci.org/reportportal/agent-ruby.svg?branch=master)](https://travis-ci.org/reportportal/agent-ruby) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`NUnit 2 agent`](https://github.com/reportportal/agent-net-nunit2)                   | [![Build status](https://ci.appveyor.com/api/projects/status/tbxdsfppppv14dfn?svg=true)](https://ci.appveyor.com/project/nvborisenko/agent-net-nunit2) | TBD        | TBD              | [![NuGet version](https://badge.fury.io/nu/reportportal.nunit.svg)](https://badge.fury.io/nu/reportportal.nunit) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Spock agent`](https://github.com/reportportal/agent-java-spock)                     | [![Build Status](https://travis-ci.org/reportportal/agent-java-spock.svg?branch=master)](https://travis-ci.org/reportportal/agent-java-spock) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`JUnit agent`](https://github.com/reportportal/agent-java-junit)                     | [![Build Status](https://travis-ci.org/reportportal/agent-java-junit.svg?branch=master)](https://travis-ci.org/reportportal/agent-java-junit) | TBD        | TBD | [![Download](https://api.bintray.com/packages/epam/reportportal/agent-java-junit/images/download.svg) ](https://bintray.com/epam/reportportal/agent-java-junit/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`JBehaive agent`](https://github.com/reportportal/agent-java-jbehave)                | [![Build Status](https://travis-ci.org/reportportal/agent-java-jbehave.svg?branch=master)](https://travis-ci.org/reportportal/agent-java-jbehave) | TBD        |  TBD | [![Download](https://api.bintray.com/packages/epam/reportportal/agent-java-jbehave/images/download.svg)](https://bintray.com/epam/reportportal/agent-java-jbehave/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Cucumber agent`](https://github.com/reportportal/agent-java-cucumber)               | [![Build Status](https://travis-ci.org/reportportal/agent-java-cucumber.svg?branch=master)](https://travis-ci.org/reportportal/agent-java-cucumber) | TBD        | TBD              | [ ![Download](https://api.bintray.com/packages/epam/reportportal/agent-java-cucumber/images/download.svg) ](https://bintray.com/epam/reportportal/agent-java-cucumber/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`SoapUI agent`](https://github.com/reportportal/agent-java-soapui)                   | [![Build Status](https://travis-ci.org/reportportal/agent-java-soapui.svg?branch=master)](https://travis-ci.org/reportportal/agent-java-soapui) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Specflow agent`](https://github.com/reportportal/agent-net-specflow)                | [![Build status](https://ci.appveyor.com/api/projects/status/k9gnrmlt3yo5gl4g?svg=true)](https://ci.appveyor.com/project/nvborisenko/agent-net-specflow) | TBD        | TBD              | [![NuGet version](https://badge.fury.io/nu/reportportal.specflow.svg)](https://badge.fury.io/nu/reportportal.specflow) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`NUnit 3 agent`](https://github.com/reportportal/agent-net-nunit)                    | [![Build status](https://ci.appveyor.com/api/projects/status/q4l1kw3xrbi79m7i/branch/master?svg=true)](https://ci.appveyor.com/project/nvborisenko/agent-net-nunit/branch/master) | TBD        | TBD              | [![NuGet version](https://badge.fury.io/nu/reportportal.nunit.svg)](https://badge.fury.io/nu/reportportal.nunit) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Scalatest agent`](https://github.com/reportportal/agent-scala-scalatest)            | [![Build Status](https://travis-ci.org/reportportal/agent-scala-scalatest.svg?branch=master)](https://travis-ci.org/reportportal/agent-scala-scalatest) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Ready! API Integration`](https://github.com/reportportal/agent-readyapi)            | NO       | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [Logging integrations](https://github.com/reportportal?utf8=%E2%9C%93&q=logger-) ||||||||||||
| [`log4net logger`](https://github.com/reportportal/logger-net-log4net)                | [![Build status](https://ci.appveyor.com/api/projects/status/649dujaserywuchy?svg=true)](https://ci.appveyor.com/project/nvborisenko/logger-net-log4net) | TBD        | TBD              | [![NuGet version](https://badge.fury.io/nu/reportportal.log4net.svg)](https://badge.fury.io/nu/reportportal.log4net) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`log4j logger`](https://github.com/reportportal/logger-java-log4j)                   | [![Build Status](https://travis-ci.org/reportportal/logger-java-log4j.svg?branch=master)](https://travis-ci.org/reportportal/logger-java-log4j) | TBD        | TBD              |  [ ![Download](https://api.bintray.com/packages/epam/reportportal/logger-java-log4j/images/download.svg) ](https://bintray.com/epam/reportportal/logger-java-log4j/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`nlog logger`](https://github.com/reportportal/logger-net-nlog)                      | [![Build status](https://ci.appveyor.com/api/projects/status/99gs8ib4ucth6uj7?svg=true)](https://ci.appveyor.com/project/nvborisenko/logger-net-nlog) | TBD        | TBD              | [![NuGet version](https://badge.fury.io/nu/reportportal.nlog.svg)](https://badge.fury.io/nu/reportportal.nlog) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`tracelistener`](https://github.com/reportportal/logger-net-tracelistener)           | TBD      | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`logback`](https://github.com/reportportal/logger-java-logback)                      | [![Build Status](https://travis-ci.org/reportportal/logger-java-logback.svg?branch=master)](https://travis-ci.org/reportportal/logger-java-logback) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`log4j2`](https://github.com/reportportal/logger-java-log4j2)                        | [![Build Status](https://travis-ci.org/reportportal/logger-java-log4j2.svg?branch=master)](https://travis-ci.org/reportportal/logger-java-log4j2) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [Common libraries](https://github.com/reportportal?utf8=%E2%9C%93&q=commons-) ||||||||||||
| [`RP Commons`](https://github.com/reportportal/commons)                               | [![Build Status](https://travis-ci.org/reportportal/commons.svg?branch=master)](https://travis-ci.org/reportportal/commons) | TBD        | TBD              | [![Download](https://api.bintray.com/packages/epam/reportportal/commons/images/download.svg) ](https://bintray.com/epam/reportportal/commons/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Validation and Error Handling common rules`](https://github.com/reportportal/commons-rules) | [![Build Status](https://travis-ci.org/reportportal/commons-rules.svg?branch=master)](https://travis-ci.org/reportportal/commons-rules) | TBD        | TBD              | TBD               | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`REST API Model`](https://github.com/reportportal/commons-model)                     | [![Build Status](https://travis-ci.org/reportportal/commons-model.svg?branch=master)](https://travis-ci.org/reportportal/commons-model) | TBD        | TBD              | [ ![Download](https://api.bintray.com/packages/epam/reportportal/commons-model/images/download.svg) ](https://bintray.com/epam/reportportal/commons-model/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Bugtracking extension`](https://github.com/reportportal/commons-bugtracking)        | [![Build Status](https://travis-ci.org/reportportal/commons-bugtracking.svg?branch=master)](https://travis-ci.org/reportportal/commons-bugtracking) | TBD        | TBD              | [ ![Download](https://api.bintray.com/packages/epam/reportportal/commons-bugtracking/images/download.svg) ](https://bintray.com/epam/reportportal/commons-bugtracking/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`DAO`](https://github.com/reportportal/commons-dao)                                  | [![Build Status](https://travis-ci.org/reportportal/commons-dao.svg?branch=master)](https://travis-ci.org/reportportal/commons-dao) | TBD        | TBD              | [ ![Download](https://api.bintray.com/packages/epam/reportportal/commons-dao/images/download.svg) ](https://bintray.com/epam/reportportal/commons-dao/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Commons codec`](https://github.com/reportportal/commons-codec-repacked)             | NO       | TBD        | TBD              | [![Download](https://api.bintray.com/packages/epam/reportportal/commons-codec-repacked/images/download.svg) ](https://bintray.com/epam/reportportal/commons-codec-repacked/_latestVersion) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |
| [`Bean objects for .NET`](https://github.com/reportportal/commons-net)                | [![Build status](https://ci.appveyor.com/api/projects/status/al55r7ou2wkx67pj?svg=true)](https://ci.appveyor.com/project/nvborisenko/commons-net) | TBD        | TBD              | [![NuGet version](https://badge.fury.io/nu/reportportal.shared.svg)](https://badge.fury.io/nu/reportportal.shared) | TBD        | TBD        | TBD     | TBD                   | TBD           | TBD           | TBD      |

## For reference
* [`RP on Travis-CI`](https://travis-ci.org/reportportal/)