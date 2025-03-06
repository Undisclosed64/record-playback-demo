# Running Selenium IDE Test on LambdaTest

This repository contains a Selenium IDE (.side) test project for the blog post demo on "Implementing Record and Playback in Selenium" for [LambdaTest](https://www.lambdatest.com/). Below are the steps for executing this test project on LambdaTest's cloud Selenium Grid:

## Prerequisites
- A [LambdaTest](https://www.lambdatest.com/) account.
- Your **LambdaTest username** and **access key**.
- **Node.js installed** on your machine.
- The **Selenium IDE Runner (SIDE Runner)** installed.

## How to Run the Test on LambdaTest

### 1. Install Selenium IDE Runner
Install SIDE Runner globally by running:

```sh
npm install -g selenium-side-runner
```

### 2. Clone This Repository
```sh
git clone https://github.com/Undisclosed64/record-playback-demo.git
cd record-playback-demo
```

### 3. Get Your LambdaTest Credentials
- Log in to [LambdaTest](https://www.lambdatest.com/).
- Navigate to the [Automation Dashboard](https://automation.lambdatest.com/build).
- Click on **Access Key** to copy your username and access key.

### 4. Execute the `.side` File Using SIDE Runner
In your terminal, navigate to the directory containing `record-playback-demo.side` file and run the following command, replacing `user-name` and `access-key` with your actual values:

```sh
selenium-side-runner "record-playback-demo.side" --server https://user-name:access-key@hub.lambdatest.com/wd/hub -c " options = ChromeOptions() options.browser_version = "latest" options.platform_name = "Windows 11""
```

### 5. View Execution Results
Once the test runs, you can check the execution details and logs in your [LambdaTest Automation Dashboard](https://automation.lambdatest.com).

## Need Help?
If you have any questions, refer to [LambdaTest Documentation](https://www.lambdatest.com/support/docs/) or create an issue in this repository or just reach out me.

---


