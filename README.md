# Querying an S3 Bucket with a Bash Script

An S3 bucket is a storage container in Amazon Simple Storage Service (S3), a cloud storage service provided by Amazon Web Services (AWS). S3 buckets are used to store and manage data in the cloud, such as objects, files, and media content. S3 buckets are similar to directories or folders in a file system, and they can be organized into a hierarchical structure. Each S3 bucket is associated with a unique name and has its own set of permissions and access control policies. S3 buckets can be accessed and managed through the AWS Management Console, the AWS command-line interface (CLI), or the AWS SDKs.

The aclś are often misconfigured allowing people to access the data stored within them

These script do the following :<BR>
-checks if an Amazon S3 bucket exists, lists the objects in the bucket, and copies a file to the bucket.<BR>
-downloads files from a public s3 bucket, checks to see which ones are text files, greps keywords from the files and saves the results to a file <BR>

The aws CLI can be downloaded from here https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
