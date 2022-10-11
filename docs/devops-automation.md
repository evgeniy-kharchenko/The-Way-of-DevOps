# DevOps Automation
Компетенции для развития в ветке `DevOps Automation`:
```mermaid
graph LR
    DevOpsAutomation{DevOps Automation}
    DevOpsAutomation --> CFMG[Configuration management]
    DevOpsAutomation --> PROG[Programming/software development]
    DevOpsAutomation --> TEST[Testing]
    DevOpsAutomation --> SINT[Systems integration and build]
    DevOpsAutomation --> RELM[Release and deployment]
    DevOpsAutomation --> DBAD[Database administration]
    DevOpsAutomation --> ITOP[IT infrastructure]

    CFMG --> IaaC[Infrastructure as Code]
    IaaC --> Ansible
    IaaC --> Cheef
    IaaC --> Puppet
    IaaC --> Salt
    IaaC --> Terraform
    IaaC --> Pulumi
    IaaC --> AWSCDK[AWS CDK]

    PROG --> ProgrammingLanguages[Programming Language]
    ProgrammingLanguages --> Java
    ProgrammingLanguages --> Go
    ProgrammingLanguages --> Python
    ProgrammingLanguages --> Shell
    ProgrammingLanguages --> SQL

    Shell --> bash
    Shell --> powershell
    Shell --> TxtEditors[Text Editors]
    TxtEditors --> Vim
    TxtEditors --> Nano
    Shell --> CompilingTools[Compiling Tools]
    CompilingTools --> gcc
    CompilingTools --> make
    Shell --> TextManipulationTools[Text Manipulation Tools]
    TextManipulationTools --> TxtManipulationTools[sed/awk/cut/uniq/*grep/fmt/tr/cat-tac/head/tail/sort/wc/jq/gron/nl]
    
    TEST --> TestingPractices[Testing Practices]
    TestingPractices --> TDD
    TestingPractices --> TDS
    TestingPractices --> ShiftLeft[Shift Left]
    TestingPractices --> Regress
    TestingPractices --> Unit[Unit Testing]
    TEST --> Frameworks
    Frameworks --> Testcontainers

    SINT --> CI[Continious Integration Practise]
    SINT --> VCS[Version control system]
    VCS --> Git
    VCS --> SVN
    SINT --> CICDTools[CI/CD Tools]
    CICDTools --> GitLab
    CICDTools --> Jenkins
    CICDTools --> GithubActions[Github Actions]
    CICDTools --> CircleCI[Circle CI]
    
    RELM --> CD[Continious Devlivery/Deployment Practise]
    RELM --> Containerization
    Containerization --> OCI[Open Container Initiative]
    Containerization --> Tools
    Tools --> Docker
    Tools --> CRI-O
    Tools --> Kaniko
    Tools --> Buildah
    Tools --> Podman
    Tools --> Skopeo
    Tools --> Crane
    RELM --> ContainerOrchestration[Container Orchestration]
    ContainerOrchestration --> Kubernetes
    ContainerOrchestration --> Nomad
    ContainerOrchestration --> Mesos
    ContainerOrchestration --> DockerSwarm[Docker Swarm]

    DBAD --> DBMS
    DBMS --> SQLDB[SQL]
    DBMS --> NoSQLDB[NoSQL]

    ITOP --> OS[Operating System]
    OS --> Networking
    Networking --> NetworkTools[Network Tools]
    NetworkTools --> NetTools[ping/tracert/ss/netstat/iptables/dig/tcpdump/nmap]
    Networking --> Protocols
    Protocols --> NetworkProtocols[Ethernet/atm/icmp/ipv4/6/arp/tcp/udp/https/smtp/ldap]
    Networking --> Web
    Web --> WebServers[Web Server]
    WebServers --> Nginx
    WebServers --> Apache
    WebServers --> IIS
    Web --> ReverseProxy[Reverse Proxy]
    Web --> CachingServer[Caching server]
    Web --> LB[Load balacner]
    Web --> Firewall
    OS --> Virtualization
    OS --> MemoryStorage[Memory/Storage]
    OS --> FS[File System]
    OS --> Sockets
    OS --> POSIX[POSIX Basics]
    OS --> Processes
    OS --> DebugTools[Debug Tools]
    DebugTools --> DebugTools1[ps/top/htop/atop/lsof/iotop/iostat/strace/df/du/lsblk/uname/history]
    OS --> Performance
    OS --> ThreadAndConcurrency[Thread and Concurrency]
    OS --> ServicesAndStartupMgmt[Services and Startup Management]
    OS --> Distributions
    Distributions --> Windows
    Distributions --> Ubuntu
    Distributions --> RHEL
    Distributions --> CentOS
    Distributions --> Debian
    Distributions --> Fedora
    ITOP --> LogsManagement[Logs Management]
    LogsManagement --> ELK
    LogsManagement --> Graylog
    LogsManagement --> Splunk
    LogsManagement --> Loki
    ITOP --> InfraMonitoring[Infrastructure Monitoring]
    InfraMonitoring --> Prometheus
    InfraMonitoring --> Zabbix
    InfraMonitoring --> Nagios
    InfraMonitoring --> Grafana
    InfraMonitoring --> Datadog
    ITOP --> AppMonitoring[Application Monitoring]
    AppMonitoring --> Jaeger
    AppMonitoring --> NewRelic[New Relic]
    AppMonitoring --> AppDynamics
    AppMonitoring --> OpenTelemetry
    ITOP --> CloudProviders[Cloud Providers]
    CloudProviders --> AWS
    CloudProviders --> GCP[Google cloud platform]
    CloudProviders --> DigitalOcean[Digital Ocean]

```