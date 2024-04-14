aws s3 cp ./simple-mern-projects.txt s3://source-training-bucket-25-01-2024/projects/simple/

aws s3 cp ./simple-web-projects.txt s3://source-training-bucket-25-01-2024/projects/simple/

aws s3 cp ./complex-mern-projects.txt s3://source-training-bucket-25-01-2024/projects/complex/

aws s3 cp ./complex-web-projects.txt s3://source-training-bucket-25-01-2024/projects/complex/

-------------------------
aws s3 ls s3://source-training-bucket-25-01-2024

aws s3 ls --recursive s3://source-training-bucket-25-01-2024

aws s3 ls s3://source-training-bucket-25-01-2024/projects/

aws s3 ls

----------------------------

aws s3 cp ./aws-cloud.txt s3://source-training-bucket-25-01-2024/courses/

aws s3 cp ./java-fsd.txt s3://source-training-bucket-25-01-2024/courses/

----------------------------

aws s3 rm s3://source-training-bucket-25-01-2024/projects/simple/simple-mern-projects.txt

aws s3 rm --recursive s3://source-training-bucket-25-01-2024/projects/


