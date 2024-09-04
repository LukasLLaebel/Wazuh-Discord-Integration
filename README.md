# Wazuh Discord Integration

This project provides an integration between [Wazuh](https://wazuh.com/), an open-source security monitoring platform, and [Discord](https://discord.com/), a popular communication platform. The integration allows Wazuh alerts to be sent directly to a specified Discord channel, enabling real-time monitoring and response for your security events.

## Features

- **Real-time Alerting:** Automatically sends Wazuh alerts to a designated Discord channel.
- **Customizable Alert Levels:** Configure the types and severity of alerts to be forwarded.
- **Easy to Deploy:** Minimal setup required; works with your existing Wazuh and Discord configurations.
- **Flexible Configuration:** Supports multiple Discord channels and webhook configurations.
- **Scalable and Secure:** Designed to handle high volumes of alerts while ensuring data integrity and privacy.

## Prerequisites

- A running instance of Wazuh Manager.
- Access to the Wazuh RESTful API.
- A Discord account and a Discord server.
- A Discord Webhook URL (for the channel where you want alerts to be sent).

This project provides an integration between [Wazuh](https://wazuh.com/), an open-source security monitoring platform, and [Discord](https://discord.com/), a popular communication platform. The integration allows Wazuh alerts to be sent directly to a specified Discord channel, enabling real-time monitoring and response for your security events.

## Features

- **Real-time Alerting:** Automatically sends Wazuh alerts to a designated Discord channel.
- **Customizable Alert Levels:** Configure the types and severity of alerts to be forwarded.
- **Easy to Deploy:** Minimal setup required; works with your existing Wazuh and Discord configurations.
- **Flexible Configuration:** Supports multiple Discord channels and webhook configurations.
- **Scalable and Secure:** Designed to handle high volumes of alerts while ensuring data integrity and privacy.

## Prerequisites

- A running instance of Wazuh Manager.
- Access to the Wazuh RESTful API.
- A Discord account and a Discord server.
- A Discord Webhook URL (for the channel where you want alerts to be sent).

## Installation
### <span style="color: red;">--- Guide NOT DONE ---</span>
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/LukasLLaebel/wazuh-discord-integration.git
    cd wazuh-discord-integration
    ```

2. **Configure the Integration:**
   Open the `config.json` file and provide your Wazuh API credentials and Discord Webhook URL:
    ```json
    {
        "wazuh": {
            "api_url": "https://your-wazuh-instance:55000",
            "api_user": "your_api_user",
            "api_password": "your_api_password"
        },
        "discord": {
            "webhook_url": "https://discord.com/api/webhooks/your_webhook_id/your_webhook_token"
        }
    }
    ```

## Configuration

- **Alert Filtering:** Customize alert types and severity levels to be sent to Discord by modifying the `alert_filters` section in the `config.json`.
- **Multiple Webhooks:** Add multiple Discord Webhook URLs if you want to send alerts to different channels.

## Usage

To start sending Wazuh alerts to Discord, simply run the integration script. You can also set up a scheduled task or cron job to run the script at regular intervals.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, reach out to `owner@lukasleander.dk`.

## Acknowledgements

- [Wazuh](https://wazuh.com/) for providing a robust security monitoring platform.
- [Discord](https://discord.com/) for their powerful and flexible communication platform.

2. **Install Dependencies:**
    Ensure you have Python and `pip` installed. Then, install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure the Integration:**
   Open the `config.json` file and provide your Wazuh API credentials and Discord Webhook URL:
    ```json
    {
        "wazuh": {
            "api_url": "https://your-wazuh-instance:55000",
            "api_user": "your_api_user",
            "api_password": "your_api_password"
        },
        "discord": {
            "webhook_url": "https://discord.com/api/webhooks/your_webhook_id/your_webhook_token"
        }
    }
    ```


## Configuration

- **Alert Filtering:** Customize alert types and severity levels to be sent to Discord by modifying the `alert_filters` section in the `config.json`.
- **Multiple Webhooks:** Add multiple Discord Webhook URLs if you want to send alerts to different channels.

## Usage

To start sending Wazuh alerts to Discord, simply run the integration script. You can also set up a scheduled task or cron job to run the script at regular intervals.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, reach out to `your_email@example.com`.

## Acknowledgements

- [Wazuh](https://wazuh.com/) for providing a robust security monitoring platform.
- [Discord](https://discord.com/) for their powerful and flexible communication platform.
