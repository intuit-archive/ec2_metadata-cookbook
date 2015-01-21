[![Build Status](https://secure.travis-ci.org/intuit/ec2_metadata-cookbook.png)](http://travis-ci.org/intuit/ec2_metadata-cookbook)

**!!! This project has been deprecated.  We recommend you search the [Chef Supermarket ](https://supermarket.chef.io/) for a supported alternative !!!**

# ec2_metadata-cookbook cookbook

# Requirements
* Chef 10.x

Platform:
* CentOS 6.x
* RHEL 6.x

# Usage
Add this cookbook to your runlist

# Attributes
* node['ec2-metadata']['version'] - version to install, default is 0.1.1-1
# Recipes
## default
Installs ec2-metadata rpm This rpm was created from the Amazon EC2 Instance Metadata Query Tool which consists of one bash script.
This rpm must be uploaded to a yum repo accessable by your system in order for this cookbook to be successful.

# Author

Author:: Intuit, Inc. (<kevin_young@intuit.com>)
