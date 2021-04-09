#   Cloudfront distributions & seprate lambda packaging to avoid unneccery duplication of code.

### 1. I tried to update existing cloudfront distribution but did't find any method in the serverless to update the existing distribution . but I find some plugins and tried the below two but unable to update.

### 2. but we can create a distribution through template and can create multiple distribution in the template.

### 3. we can create individual packages of each lambda to avoiding duplication of unneccery code.