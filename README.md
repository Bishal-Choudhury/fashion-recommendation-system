<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fashion Recommender System</title>
</head>

<body>

    <h1>Fashion Recommender System</h1>

    <p>Welcome to the Fashion Recommender System! This system utilizes a large fashion product image dataset to recommend similar products based on their features.</p>

    <h2>Dataset</h2>

    <h3>Kaggle Datasets:</h3>

    <ul>
        <li>
            <strong>Big Size (25 GB):</strong>
            <a href="https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset">Download Kaggle Big Size Dataset</a>
        </li>
        <li>
            <strong>Small Size (593 MB):</strong>
            <a href="https://www.kaggle.com/paramaggarwal/fashion-product-images-small">Download Kaggle Small Size Dataset</a>
        </li>
    </ul>

    <h3>Google Drive Links:</h3>

    <ul>
        <li>
            <strong>Pickle File for Feature Embedding:</strong>
            <a href="https://drive.google.com/file/d/1X0g_qgZtQ-iMfECOOlPOuHNlUp8j1VDJ/view?usp=sharing">Download Feature Embedding Pickle File</a>
        </li>
        <li>
            <strong>Small Dataset:</strong>
            <a href="https://drive.google.com/file/d/1xe5Fb5PatnI8eYOqBWrNaUvSz82b-tiJ/view?usp=sharing">Download Small Dataset</a>
        </li>
    </ul>

    <h2>Instructions</h2>

    <p>Follow these steps to get started:</p>

    <ol>
        <li>Install the required dependencies using pip:</li>
        <code>pip install -r requirements.txt</code>
        <p>Make sure to check compatibility with your system.</p>

        <li>Download the fashion dataset from any of the Kaggle links mentioned above.</li>

        <li>Verify that you have both pickle files (<code>embeddings.pkl</code> and <code>filenames.pkl</code>) installed.</li>

        <li>Ensure all files are in the same directory.</li>

        <li>To launch the web server, execute the following command:</li>
        <code>streamlit run main.py</code>
    </ol>

    <p>Feel free to explore and enjoy the Fashion Recommender System! If you encounter any issues, don't hesitate to reach out.</p>

</body>

</html>
