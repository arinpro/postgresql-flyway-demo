# PostgreSQL Flyway Demo

This repository demonstrates how to setup Database CI/CD using [Flyway](https://flywaydb.org/) and [GitHub Actions](https://github.com/actions) to manage database migrations for a PostgreSQL database.🚀

## Getting Started

To get started with this demo:

1. Fork the repository to your own GitHub account.

2. Create GitHub Actions Secrets and store appropriate database URL, user and password.

3. Whenever a new SQL script is added to the migrations folder, the workflow will automatically execute and apply any pending migrations to your database in a sequential order.<br/>**Note**: Make sure to delete any existing scripts in the migrations folder to avoid any unnecessary migrations.

4. Open a PostgreSQL client (such as [pgAdmin](https://www.pgadmin.org/)) and connect to the database. You should see the migrations applied by the database migrations.

Looking for a detailed how-to guide? Take a look 👉 [here](https://dbaguides.com/setup-database-cicd-for-postgresql-using-flyway-and-github-actions). 

## About Flyway

[Flyway](https://flywaydb.org/) is an open-source database migration tool. It allows you to manage database schema changes and data migrations as code, making it easier to keep your database changes under version control and automate the deployment process.

## Contributing
Contributions are always welcome! If you have any ideas for how to improve this demo, feel free to open an issue or submit a pull request.🙏

## License

This repository is licensed under the Apache-2.0 license. See the [LICENSE](LICENSE) file for details.



