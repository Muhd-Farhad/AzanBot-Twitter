# 🕌 AzanBot-Twitter

A Twitter bot notifier for azan in Malaysia, using data from Jabatan Kemajuan Agama Islam Malaysia (JAKIM). 

## Features

- User need to specify their own Twitter API key inside `config.py`.
- Users can specify daerah or state zone inside `config.py`.
- All logs will be stored inside a log file.
- No need to set local timezone of the host.

## Usage

To use the AzanBot-Twitter, follow these steps:

1. Clone this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Set up your Twitter API key inside `config.py`.
4. Specify the daerah or state zone inside `config.py`.
5. Run `python azanbot.py` to start the bot.

## Future Plans

- Add more error handling.
- Add seasonal hashtags to be set.
- Add random quote generation.

## Contribution

Contributions to AzanBot-Twitter are always welcome! To contribute, follow these steps:

1. Fork this repository.
2. Create a new branch with a descriptive name.
3. Make your changes and test them.
4. Commit your changes and push them to your fork.
5. Create a pull request to this repository.

## FAQ

**Q:** Can I use this bot for other countries?

**A:** Currently, this bot only works for Malaysia. However, you can modify the code to work with other countries.

**Q:** How often does the bot check for azan times?

**A:** The bot refreshes for azan times every day at 12:05 AM

**Q:** How do I get Twitter API key?
To get Twitter API keys, you need to create a Twitter Developer Account and then create a Twitter App. Here are the steps to follow:

**A:** Go to https://developer.twitter.com/en/apps and sign in to your Twitter account.
Click the "Create an app" button.
Fill out the application details (name, description, website, etc.).
Agree to the Twitter Developer Agreement and click "Create".
Once your app is created, click on the "Keys and Tokens" tab.
Generate your consumer key and consumer secret, then generate your access token and access token secret.

**Q:** How do I know what code for specific timezone?
**A:** Can refer to https://www.e-solat.gov.my/. For example for KL, I will specify WLY01 under ZONE inside config.py
## License

This project is licensed under the [MIT License](LICENSE).
