# 📚 Proyek 2 Money Tracker App - Google Cloud Engineer

Submission Proyek Money Tracker App - Menjadi Google Cloud Engineer

## Requirements

Google Cloud Platform - (google-compute-service = App Engine &  google-storage-service = Bucket)

### Set-up and Run
> now install dependencies and run the project 
> [Website](http://frontend.submission-mgce-ikhsan-424602.et.r.appspot.com)

```shell
$ gcloud app deploy
$ gcloud app browse
```

- **[Documentation](https://cloud.google.com/appengine/docs/standard/hosting-a-static-website)**

> ## fix app.yaml update

```shell
runtime: php81
env: standard
service: frontend

handlers:
- url: /.*
  script: auto
```

## Authors

Contributors names and contact info

Mr.Sanz

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
