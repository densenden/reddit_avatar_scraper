# Reddit User Image Scraper

This repository contains a Reddit User Image Scraper that fetches user avatars from specified subreddits. The scraped images can be used for training image classification models.

## Use Cases

1. **Image Classification Model Training**: Use the scraped images to train machine learning models for image classification tasks.
2. **Data Augmentation**: Enhance your dataset with diverse images from various Reddit users.
3. **Research**: Collect data for research purposes, such as studying user behavior or avatar trends on Reddit.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/densenden/reddit-user-image-scraper.git
    cd reddit-user-image-scraper
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure Tor is installed and running:
    ```bash
    brew install tor
    brew services start tor
    ```

## Usage

1. Run the scraper:
    ```bash
    python data/scraper_setup.py
    ```

2. Follow the prompts to enter the subreddit name and the folder name for saving the images.

## Configuration

- **Tor Configuration**: Ensure Tor is running on your machine. The scraper uses Tor to route requests through a SOCKS proxy for anonymity.
- **Proxy Settings**: The scraper is configured to use the SOCKS proxy provided by Tor.

## License

This project is licensed under the MIT License.
