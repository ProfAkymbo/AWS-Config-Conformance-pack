# AWS-Config-Conformance-pack
This folder contains Conformance pack using CloudFormation for a compliance remediation. 
We are implementing a solution to enforce use of a required tag upon creation of EC2 instances. 
The instances would be terminated if AWS Config detects any non-compliant instance and a remediation to prevent it would be auto-remediated with the system manager automation document . 
### Reference 
https://asecure.cloud/a/cfgrule_required-tags/
https://aws.amazon.com/blogs/mt/tag-workloads-with-aws-config-conformance-packs-across-aws-accounts/
