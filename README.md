# Google Image Scraper

A Python-based tool to scrape and download images from Google Search.\
This project allows you to fetch a specified number of images for any
keyword and store them locally in an organized folder structure.

------------------------------------------------------------------------

## 🚀 Features

-   Search any keyword (e.g., "dogs", "cars", "flowers").
-   Specify the number of images to download.
-   Automatically saves images to your local system.
-   Useful for dataset creation (ML/DL projects) or personal use.

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   Python 3.x
-   Jupyter Notebook

### Libraries Used

-   `requests`
-   `beautifulsoup4`
-   `os`
-   `shutil`
-   `urllib`
-   `selenium` *(if included)*

------------------------------------------------------------------------

## 📂 Project Structure

    ├── Google Image Scrapping.ipynb   # Main Jupyter Notebook
    ├── images/                        # Downloaded images (auto-created)
    ├── README.md                      # Project Documentation

------------------------------------------------------------------------

## ⚙️ Installation & Usage

1.  Clone this repository or download the notebook:

    ``` bash
    git clone https://github.com/your-username/google-image-scraper.git
    ```

2.  Install the required libraries:

    ``` bash
    pip install requests beautifulsoup4 selenium
    ```

3.  Run the notebook:

    ``` bash
    jupyter notebook Google\ Image\ Scrapping.ipynb
    ```

4.  Enter your search keyword and number of images to download.

------------------------------------------------------------------------

## 📸 Example

If you search for **"cats"** with 20 images:\
- The scraper will create a folder `images/cats/`\
- Save 20 cat images in that folder.

------------------------------------------------------------------------

## 💡 Applications

-   Build custom datasets for **Machine Learning** / **Deep Learning**.
-   Collect research images.
-   Personal image collections.

------------------------------------------------------------------------

## ⚠️ Disclaimer

This project is for **educational purposes only**.\
Scraping Google Images may violate Google's terms of service.\
Use it responsibly and only for personal/research purposes.

------------------------------------------------------------------------

## 👨‍💻 Author

-   **Your Name**\
-   GitHub: [your-username](https://github.com/your-username)\
-   LinkedIn: [your-link](https://linkedin.com/in/your-profile)
