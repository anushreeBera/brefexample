## Reader Lambda Instance

This Lambda instance is responsible for picking up message from SQS, reading the data from the DB and storing it in S3.


### Installation
- Clone the repository.
- Run `composer install`.
- Run `cp .env.example .env`.
- Update the `.env` file with the correct values.

## Deployment

### Non Prod Environment
- `php artisan config:clear`
- `serverless deploy`
- To remove a deployment `serverless remove`

### Prod Environment
- https://bref.sh/docs/deploy#deploying-for-production


## Dependencies

- [Laravel Framework](https://laravel.com).
- [bref.sh](https://bref.sh/).
