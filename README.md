# How to run

1. Download and install the latest version of node 16 for your operating system
    - https://nodejs.org/download/release/v16.19.0/
2. Install git:
    - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
3. Authenticate your Github account with Git:
    - https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git
4. Clone this repo using your command line
    - `git https://github.com/cheaper-eater/backend.git`
5. Setup env variables
    - in your command line, navigate to the project directory you cloned
    - in the root of the project, create a file `.env`
    - in the `.env` file add a line `MONGO_URI=mongodb+srv://cheapereater:<password>@cheapereater.t9lwwta.mongodb.net/<dbname>`
      replacing the <password> with the shared password found in our discord credentials channel and <dbname> with the name of
      the database you want to use. For testing, dbname can be set to "test" without quotes.
5. Build and run:
    - in your command line, run `npm install` to install all of the project dependencies
    - run with `npm run start`
