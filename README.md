# AWS S3 cURL File Uploader

## Usage
./aws_s3_curl.sh NameOfS3Bucket AccessKeyID SecretKey /path/to/file

## Required Options
NameOfS3Bucket

Specify the name your S3 bucket. For example to upload a new file to your
website www.example.com then the name of the bucket is www.example.com

AccessKeyID

Specify the Access Key ID of the user and the group you created in IAM that
allows uploading new files to your S3 bucket.

SecretKey

Specify the Secret Key that's associated with the Access Key ID. You may have to
create a new Access Key ID to see its Secret Key.

/path/to/file

Specify the absolute path to a single file to be uploaded to your S3 bucket.

