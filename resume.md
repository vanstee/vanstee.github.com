---
layout: page
title: Résumé
---

[Focus](#focus)<br>
[Work History](#work-history)<br>
[Community](#community)<br>
[Open Source](#open-source)<br>
[Education](#education)<br>

{:.border .gray .my3}
* * *

# Focus

I've been writing software for over 14 years. Most of that time has been spent
building web applications, working with distributed systems, managing
infrastructure, and thinking about product direction. But, in general, I love
solving hard and unique problems, learning about how everything works
throughout the entire stack, and, even more so, seeing how systems fail.

The sweet spot between my interests and experience would be working on the
backend or infrastructure side of a product as part of a team of happy
developers with an engineering culture that promotes high-quality, maintainable
code. Better yet, providing product direction and system design for technical,
developer-focused products would be an ideal fit.

{:.border .gray .my3}
* * *

# Work History

## [Salesforce](https://salesforce.com) &mdash; Principal Software Engineer

Spring 2017 - Today

Designed and built internal tools to build and deploy code, manage
infrastructure, automate manual workflows, and increase developer productivity.
Lead a team of developers, planned future projects, set priorities, interviewed
and hired team members, and continuously pushed to improve all of our tooling
and process along the way, not only to help our team but for the entire
organization and other teams across Salesforce.

### Projects

* Developed and rolled out a Patching Automation Service to manage the
  application lifecycle and safely apply RPM upgrades to traditional mutable
  infrastructure written in Go as a HTTP server and CLI client, greatly
  reducing the manual effort required to keep our servers patched.
* Built and supported Terraserver, a Terraform as a Service product, to allow
  anyone with access the ability to make approved changes to infrastructure;
  written in Go as a gRPC server, with a CLI client
* Helped plan and implement a migration from our existing data centers to AWS
  (~2000 servers), by defining all of our resources in modularaized Terraform
  code and helping to move towards a cloud-native architecture
* Planned and migrated our entire build system (~100 application pipelines) to
  Buildkite with Docker, docker-compose, Buildkit, and a custom Go CLI for
  common actions
* Built and managed the path to production for over 150 developers (Build
  Service, Deploy Service, Compliance Service, Artifactory, GitHub Enterprise,
  Chatbots, and a whole slew of other tools)
* Migrated all of our internal applications to Heroku's Container Runtime and
  helped integrate building and deploying containers from our deployment system

## [Operable](https://operable.io) &mdash; Senior Software Developer

Spring 2015 - Spring 2017

Developed a chatbot built for enterprise companies and real world devops
workflows. Worked with users to define new features, build integrations,
support installations, and fix bugs.

### Projects

* Built-out main features of [Cog](https://github.com/operable/cog), the chat
  bot in Elixir and Erlang including chat adapters, communication over MQTT,
  authorization rules, an HTTP API, and CLI tool
* Wrote command bundles for a variety of services used to deploy, manage, and
  monitor infrastructure: [CloudFormation](https://github.com/cogcmd/aws-cfn),
  [EC2](https://github.com/cogcmd/aws-ec2),
  [S3](https://github.com/cogcmd/aws-s3),
  [GitHub](https://github.com/cogcmd/github),
  [Heroku](https://github.com/cogcmd/heroku),
  [DataDog](https://github.com/cogcmd/datadog),
  [Grafana](https://github.com/cogcmd/grafana)
* Designed and developed a bundle registry for users to upload, install, and
  view documentation for bundles
* Wrote a fully spec compliant, simple parser-combinator
  [Mustache parser](https://github.com/operable/fumanchu) 
* Built enhancements for and helped maintain
  [Relay](https://github.com/operable/go-relay), our command executor, written
  in Golang which interfaces with Docker

## [Assembly](http://assemblymade.com) &mdash; Product Developer

Winter 2014 - Spring 2015

Worked on developing and shipping products as part of the community for the
core Assembly platform. Also helped interview candidates and build an
engineering culture as part of the founding team.

#### Projects

* [Took](https://github.com/asm-helpful/helpful-web)
  [three](https://github.com/asm-products/firesize)
  [products](https://github.com/asm-products/signupsumo-web) from idea to
  launch; now used by over a thousand small businesses
* Organized and worked with a remote team (in over ten countries) to direct
  product development and accept contributions
* Designed and built a dashboard used by tens of thousands of users
* Developed a project management tool used to organize hundreds of products
* Interviewed candidates for developer and product roles

## [Big Nerd Ranch](https://www.bignerdranch.com) &mdash; Ruby Developer

Summer 2011 - Winter 2014

Worked with clients to design, develop and build a number of HTTP APIs using
many different databases with different performance requirements. Managed
projects as a team lead, prioritizing and assigning work. Also worked as a
project manager for a few small internal tools teams. Eventually, transitioned
to the Product Team tasked with designing and developing a SaaS product.

#### Projects

* Scaled a highly available HTTP API from 250 to over 500 requests per second
* Managed 60+ EC2 servers with Chef in multiple regions and availability zones
* Built a fault-tolerant analytics aggregator with Hadoop, Scribe, and Redis to
  store and query over 10 TB of user data each month
* Designed and developed a web interface and HTTP API for a conference room
  scheduling application
* Wrote a CSV processing system for importing and altering records from an API
* Developed a translation, localization, and publication HTTP API for an
  iPhone, iPad, and Mac app
* Organized the [Atlanta Ruby Users Group](https://www.meetup.com/atlantaruby/)
* [Presented on Raft at RubyConf 2013](https://www.youtube.com/watch?v=IsPxhZ2IsWw)

## [Zurb](http://zurb.com) &mdash; Ruby and JavaScript Developer

Winter 2010 - Spring 2011

Worked remotely on Ruby web applications. Developed and released browser
extensions as clients of an HTTP API.

#### Projects

* Rewrote `delayed_job` to acquire locks, update status, and return results via
  an authenticated HTTP API
* Wrote browser extensions for Safari, Chrome, and Firefox in JavaScript, which
  took full page screenshots of web sites and uploaded results to S3

## [Clemson](http://www.clemson.edu/cecas/departments/computing/index.html) &mdash; Undergraduate Researcher

Fall 2009 - Winter 2011

Researched and developed proof of concept distributed systems and web
applications for research teams in other departments. Gave presentations to
other researchers and presented a few lectures to Computer Science students.

#### Projects

* Wrote a simple P2P file sharing system in Python
* Researched and wrote a tiny distributed hash table script that communicated
  via HTTP
* Lectured about CAP, ACID, and NoSQL databases
* Presented on FUSE and meta-programming in Python
* Developed a grade management system in Java and Stripes for evaluating the
  effectiveness of quiz questions

{:.border .gray .my3}
* * *

# Community

* Organized and hosted the [Atlanta Ruby Users Group](https://www.meetup.com/atlantaruby/) since 2012
* Started the [Atlanta Elixir Users Group](https://www.meetup.com/atlantaelixir/) in 2013
* Gave a talk titled ["Raft: Consensus for Rubyists"](https://speakerdeck.com/vanstee/raft-consensus-for-rubyists) at [RubyConf 2013](https://www.youtube.com/watch?v=IsPxhZ2IsWw)
* Won 1st place at StartupWeekend Atlanta 2014
* Gave a [number of other talks](https://speakerdeck.com/vanstee) at local meetups

{:.border .gray .my3}
* * *

# Open Source

* [Cog](https://github.com/operable/cog/commits/master?author=vanstee) &mdash; Core Team
* [Grocer](https://github.com/grocer/grocer/commits/master?author=vanstee) &mdash; Core Team
* [Fumanchu](https://github.com/operable/fumanchu/commits/master?author=vanstee) &mdash; Author
* [Hovercraft](https://github.com/vanstee/hovercraft/commits/master?author=vanstee) &mdash; Author
* [Buildx](https://github.com/docker/buildx/commits?author=vanstee) &mdash; Contributor
* [Elixir](https://github.com/elixir-lang/elixir/commits/master?author=vanstee) &mdash; Contributor
* [RSpec](https://github.com/rspec/rspec-core/commits/master?author=vanstee) &mdash; Contributor
* [Sunspot](https://github.com/sunspot/sunspot/commits/master?author=vanstee) &mdash; Contributor

View more at [github.com/vanstee](https://github.com/vanstee)

{:.border .gray .my3}
* * *

# Education

Clemson University<br>
Computer Science BS<br>
Graduated Spring 2011<br>
