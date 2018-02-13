# Controlling User Access to the AWS Management Console<a name="console_controlling-access"></a>

Users who sign in to your AWS account through the sign\-in page can access your AWS resources through the AWS Management Console to the extent that you grant them permission\. The following list shows the ways you can grant users access to your AWS account resources through the AWS Management Console\. It also shows how users can access other AWS account features through the AWS website\.

**Note**  
There is no charge to use IAM\.

**The AWS Management Console**  
You create a password for each user who needs access to the AWS Management Console\. Users access the console via your IAM\-enabled AWS account sign\-in page\. For information about accessing the sign\-in page, see [The IAM Console and Sign\-in Page](console.md)\. For information about creating passwords, see [Managing Passwords](id_credentials_passwords.md)\.

**Your AWS resources, such as Amazon EC2 instances, Amazon S3 buckets, and so on**  
Even if your users have passwords, they still need permission to access your AWS resources\. When you create a user, that user has no permissions by default\. To give your users the permissions they need, you attach policies to them\. If you have many users who will be performing the same tasks with the same resources, you can assign those users to a group, then assign the permissions to that group\. For information about creating users and groups, see [Identities \(Users, Groups, and Roles\)](id.md)\. For information about using policies to set permissions, see [Access Management](access.md)\.

**AWS Discussion Forums**  
Anyone can read the posts on the [AWS Discussion Forums](https://forums.aws.amazon.com/)\. Users who want to post questions or comments to the AWS Discussion Forum can do so using their user name\. The first time a user posts to the AWS Discussion Forum, the user is prompted to enter a nickname and email address for use only by that user in the AWS Discussion Forums\. 

**Your AWS account billing and usage information**  
You can grant users access your AWS account billing and usage information\. For more information, see [ Controlling Access to Your Billing Information](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/control-access-billing.html) in the *AWS Billing and Cost Management User Guide*\. 

**Your AWS account profile information**  
Users cannot access your AWS account profile information\.

**Your AWS account security credentials**  
Users cannot access your AWS account security credentials\.

**Note**  
IAM policies control access regardless of the interface\. For example, you could provide a user with a password to access the AWS Management Console, and the policies for that user \(or any groups the user belongs to\) would control what the user can do in the AWS Management Console\. Or, you could provide the user with AWS access keys for making API calls to AWS, and the policies would control which actions the user could call through a library or client that uses those access keys for authentication\.