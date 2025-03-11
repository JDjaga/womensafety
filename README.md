# Women Safety App

This repository contains a Flutter application focused on promoting women's safety by providing up-to-date news and resources related to women's welfare.

## Features

- **News Section**: Displays the latest articles on women's safety initiatives, educational empowerment, technological advancements, self-defense programs, entrepreneurial achievements, and legal reforms.

- **Interactive Articles**: Users can tap on news cards to read full articles in their browser.

## Screenshots

![Screenshot 1](https://example.com/screenshot1.png)
![Screenshot 2](https://example.com/screenshot2.png)

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)

### Installation

1. Clone the repository:
   
git clone https://github.com/GnaneshK24/womensafety.git
Navigate to the project directory:

cd womensafety
Install dependencies:

flutter pub get
Run the application:

flutter run
Code Overview
news_page.dart
This file defines the NewsPage widget, which presents a list of news articles. Each article displays an image and title, and tapping on it opens the full article in the browser.

#Key Components:

newsArticles: A list of maps containing article details such as title, image URL, and article URL.

_openNews: A method that uses the url_launcher package to open a given URL in the external browser.

build: A method that constructs the UI, including an AppBar and a ListView.builder to display each news article as a card.

#Dependencies
flutter/material.dart
url_launcher
Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

#License
This project is licensed under the MIT License.

