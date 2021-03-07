### Architecure Diagram
<img src="images/Architure Diagrma.JPG" >

Draw Diagram online : 
- https://app.diagrams.net/

### AWS Cloud Development Kit (CDK) 
<img src="images\AWS CDK.JPG" >

### Anatomy of an app
<img src="images\AnatomyApp.JPG" >

### Project In Action
- Pre Requisite : awscli , npm , aws-cdk
- Initialize the project
```
npm install -g aws-cdk          # Install cdk 
mkdir app                       # cdk init needs an empty dir .Create an empty one for app
cd app
cdk init                        # Inialize cdk
cdk init app -l=typescript      # Initialize cdk for a particular language (typescript) for appname app
```
- entry point for our project 
```
`app\bin\app.ts`

const app = new cdk.App();

```
