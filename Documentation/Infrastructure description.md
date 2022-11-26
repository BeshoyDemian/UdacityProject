[AWS Infrastructure Description](./Documentation/infrastructure%20Diagram.png)

we had 3 parts 

1- S3 bucket for saving files :- https://s3.console.aws.amazon.com/s3/buckets/beshoy-udagram?region=us-east-1&tab=objects

*There is a 33 folder in screenshots showing the structure of this S3

2- RDS for database running with postgres db on free tier with puplic access 
url :- https://us-east-1.console.aws.amazon.com/rds/home?region=us-east-1#database:id=udagram1;is-cluster=false;tab=connectivity

with Endpoint :- udagram1.cklfzlumqef9.us-east-1.rds.amazonaws.com

*There is a RDS folder in screenshots showing the properties of this RDS 

3- Elastic Beanstalk For backend save on bucket and used to be consumed with our front end

url :-http://udagram-api-dev.eba-yankcaag.us-east-1.elasticbeanstalk.com/

*There is a Elastic Beanstalk folder in screenshots showing the properties of this EB 
