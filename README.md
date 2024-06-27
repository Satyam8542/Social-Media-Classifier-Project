# Social Media Post Classifier

This project aims to classify social media posts into categories such as informative, promotional, and personal using a rule-based approach. By leveraging predefined keywords and simple text processing techniques, it provides a straightforward method for categorizing posts without the need for machine learning.

## Features

- **Rule-Based Classification**: Uses predefined keywords to classify posts.
- **Text Preprocessing**: Converts text to lowercase, removes punctuation, and tokenizes the text.
- **Web Interface**: Built with Flask, allowing users to input and classify posts in real-time.

## Project Structure

social_media_classifier/
├── app.py
├── templates/
│ └── index.html
└── static/
└── styles.css

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/social_media_classifier.git
    cd social_media_classifier
    ```

2. **Create a virtual environment and activate it**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install flask
    ```

## Usage

1. **Run the Flask app**:
    ```bash
    python app.py
    ```

2. **Open your browser and go to**:
    ```
    http://127.0.0.1:5000/
    ```

3. **Classify posts**:
    - Enter a social media post in the text area.
    - Click the "Classify Post" button.
    - View the classified category of the post.

## Example Posts

```plaintext
1. Check out our new product! It's amazing and on sale now.
   - Classified as: promotional

2. Had a great time with family today at the park!
   - Classified as: personal

3. Breaking news: Scientists discover a new planet.
   - Classified as: informative

4. Don't miss out on our exclusive offer, only for today!
   - Classified as: promotional
