# *\<project-name-here\>*

*\<Brief description of project here\>*

## Installation

To install the project dependencies, you will need to have R and with the renv package installed on your system. Once you have these installed, you can follow these steps:

1. Clone the project repository to your local machine.
2. Open the project in RStudio or your preferred R IDE.
3. Open the R console. The renv environment will automatically be initialized.
4. Once the renv environment is initialized, run the following command to install the project dependencies:

   ```
   renv::restore()
   ```

   This will install all the required packages in the renv environment.

## Usage

To use this project, you can follow these steps:

1. Open the project in RStudio or your preferred R IDE.
2. Open the R console. The renv environment will automatically be activated.
3. Once the renv environment is activated, you can run the project code by opening the relevant R script/markdown files and clicking the "Run" button in your IDE.
4. Any R packages that are subsequently installed and used in the project should be captured as new R package dependencies by running the following command in the R console:

   ```
   renv::snapshot()
   ```

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the project repository to your own GitHub account.
2. Clone the forked repository to your local machine.
3. Create a new branch for your changes.
4. Make your changes and commit them to your branch.
5. Push your branch to your forked repository.
6. Open a pull request to the original project repository.