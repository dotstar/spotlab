# AWS Spot Immersion Day
## July 2019


SpotLab_v4.pdf describes detailed lab instructions.

Other content supports running CLI commands, prescribed in the lab instructions

#### 01-create-launch-template

Runs AWS CLI commands to create a launch template.  A launch template encapsulates many of your preferences for EC2 configuration so that you don't need to re-select them every time you create a new instance.

#### 02-describe-instances

AWS CLI command to show which instances are running in your account.  Uses jq, if available, to parse the JSON into a condense format.

#### 03-run-instances

Create Spot instance from the AWS CLI

#### 04-create-fleet

Create Spot fleet from the AWS CLI

#### 05-hibernation

Create a spot instance, with hibernate enabled.  On instance interruption, these instance hibernate to disk, re-starting when spot instance becomes available at the prescribed price.

#### calcpi.py

Used in hibernation lab.  Calculate pi to 999,999,999 digits.



> Last edited: Dave Dickerson 03 July 2019
