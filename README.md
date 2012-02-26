# VSPLF Dynamic I18N Framework

https://github.com/vsplf/vsplf-dynamic-i18n/wiki


## How to develop


### Prepare your environment

Use [Apache Maven][maven] version 3.0.0 minimum. Version 3.0.3 and above is recommended.

[maven]: http://maven.apache.org "Apache Maven"

### Default Build

Use this command to build project:

<pre>
  mvn clean install
</pre>

### Violations Checking Build

To check any violations, use this command below:

<pre>
  git submodule init
  git submodule update
  mvn clean install -Dvsplf.violations.checking
</pre>

### Project resources

* Issues management: https://github.com/vsplf/vsplf-dynamic-i18n/issues
* Jenkins continuous integration build: https://vsplf.ci.cloudbees.com/job/vsplf-dynamic-i18n-master-ci/ ![Build on CloudBees](http://www.cloudbees.com/sites/default/files/Button-Built-on-CB-1.png)
* Artifact deployment:
  * release repository:  https://repository-vsplf.forge.cloudbees.com/release/
  * snapshot repository: http://repository-vsplf.forge.cloudbees.com/snapshot/

### Logging


## How to use this framework
