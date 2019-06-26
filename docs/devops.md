# DevOps

## Table of Contents

* Language
  * Python
  * Ruby
  * Node.js
  * Go
  * Rust
  * C / C++
* OS Concepts
  * Process Management
  * Threads and Concurrency
  * Sockets
  * I/O Management
  * Virtualization
  * Memory/Storage
  * File System
* Managing Servers
  * Operating System
    * Linux
    * Unix
    * Windows
  * Terminal
    * Bash Scripting
      * Basics
      * Vim/Nano/PowerShell/Emacs
      * Compiling apps from source
        * gcc/make
      * System Performance
        * nmon, iostat, sar, vmstat
      * Text Manipulation Tools
        * awk, sed, grep, sort, uniq, cat, cut, echo, fmt, tr, nl, egrep, fgrep, wc
      * Process Monitoring
        * ps, top, htop, atop, isof
      * Nerwork
        * nmap, tcpdump, ping, mtr, traceroute, airmon, airodump, dig, iptables
      * Others
        * strace, dtrace, systemtap, uname, df, history
* [Networking and Security](#networking-and-security)
  * DNS
  * OSI Model
  * HTTP
  * HTTPS
  * FTP
  * SSL / TLS
* What is and how to setup
  * Reverse Proxy
  * Forward Proxy
  * Caching Server
  * Load Balancer
  * Firewall
  * Web Server
    * IIS
    * Apache
    * Nginx
    * Tomcat
    * Caddy
* [Infrastructure as a Code](#infrastructure-as-a-code)
  * [Containers](#containers)
  * Configuration Management
    * Ansible
    * Chef
    * Salt
    * Puppet
  * [Container Orchestration](#container-orchestration)
  * Infrastructure Provisioning
    * Terraform
    * Cloud Formation
* CI/CD Tool
  * Jenkins
  * Travis CI
  * TeamCity
  * Drone
  * CircleCI
* [Monitor Software and Infrastructure](#monitor-software-and-infrastructure)
  * Infrastructure Monitoring
    * Nagios
    * Icinga
    * Datadog
    * Zabbix
    * Monit
  * Application Monitoring
    * AppDynamics
    * New Relic
  * [Logs Management](#logs-management)
* Cloud Providers
  * AWS
  * Google Cloud
  * Azure
  * Digital Ocean
  * Heroku
* Techniques
  * Four key metrics
  * Secret as a Service
* Miscellaneous


## DevOps Culture

* Increased collaboration
* Team culture
  * Shared responsibility
    * Feedback
    * Automation
    * Build quality in
* Organizational culture
  * No silos
  * Autonomous teams


## Networking and Security

### HTTPS

* [HTTPS Everywhere](https://www.eff.org/https-everywhere)
* [Caddy](https://caddyserver.com/)

### HTTP2

* [HTTP2](https://hpbn.co/http2/)

## Infrastructure as a Code

### Containers

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)
* rkt
* LXC

### Container Orchestration

* [Kubernetes](https://kubernetes.io/)
  * [kompose](https://github.com/kubernetes/kompose/)
* Docker Swarm
* Mesos
* Nomad


## Continuous Integration

* Maintain a Single Source Repository
* Automate the Build
* Make Your Build Self-Testing
* Everyone Commits To the Mainline Every Day
* Every Commit Should Build the Mainline on an Integration Machine
* Fix Broken Builds Immediately
* Keep the Build Fast
  * Deployment pipeline (build pipeline / staged build)
* Test in a Clone of the Production Environment
* Make it Easy for Anyone to Get the Latest Executable
* Everyone can see what's happening
* Automate Deployment

1. Get the build automated


## Monitor Software and Infrastructure

### Logs Management

* ELK Stack
* Graylog
* Splunk
* Papertrail
* EFK Stack (Elasticsearch, Fluentd and Kibana)


## Infrastructure as a Service

* [Digital Ocean](https://www.digitalocean.com/) for simple servers.
* [Heroku](https://www.heroku.com/) for simple and integrated server and deployments
* [Now](https://zeit.co/now) for super simple deployments.
* [Firebase](https://firebase.google.com/) for managed infrastructure and databases (especially for mobile apps)
* [AWS](https://aws.amazon.com/) for pretty much anything you want so you never have to think about managing servers in your life (More on this in the “Other Trends” section)

## Platform as a Service / Backend as a Service

* [AppSync](https://aws.amazon.com/appsync/)
* [Amplify](https://aws-amplify.github.io/)
* [App Services](https://azure.microsoft.com/en-us/services/app-service/)
* [App Engine](https://cloud.google.com/appengine/)


## Miscellaneous

* [namecheap](https://www.namecheap.com/)
* [Let's Encrypt](https://letsencrypt.org/)

---

* Continuous Integration
  * Ensure everyone's changes integrate
  * Catch bugs
  * Reduce merge conflicts
* Continuous Delivery
  * Develop to release at any time
* Continuous Deployment
  * Deploy new features immetiately
* Webhooks
  * Send messages to external systems about activity in your projects
* Workflow strategies
  * No universal solution
  * Tools, process, and people
  * Flexibility is key
  * Branching
    * The github flow
      * Pull request
  * Complex workflows
    * Git Flow
      * Long lived branches
      * Simultaneous development
      * New features & current releases
      * Develop -> Feature -> Develop -> Release -> Master (tag v1.2)
      * Master -> Hotfix -> Master (tag v1.2.1)
* Managing Projects
  * Tools, Process, and People
  * Planning work
  * Removing obstacles
  * Ensuring effective communication
  * GitHub
    * Issues
    * Pull request
    * Milestone
    * Managing Information
    * Projects
* Quality Control
  * Pre-receive Hooks (enterprise only)
    * Business rules
    * Regulartory compliance
    * Prevent mistakes
  * Statuses (Code Review)
  * Protected Branches
* Getting insight into work
  * Pulse
  * Branch data
  * Graphs
* Find what you need
  * File name
  * History
  * Projects
  