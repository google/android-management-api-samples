# Android Management API Samples

This repository contains Python notebooks for getting started with the
[Android Management API](https://developers.google.com/android/management).

## Prerequisite: Google Cloud Project Setup
Before running the notebooks, you will need your own Google Cloud Project with OAuth credentials:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Navigate to **APIs & Services > OAuth consent screen** and finish configuring the consent screen.
3. Click **Audience** in the left navigation menu. Under the **Test users** section, click **Add users**, enter your email address in the side panel, and click **Save** (or click **Publish App** to push it to production).
4. Navigate to **APIs & Services > Credentials**.
5. Click **Create Credentials > OAuth client ID**, and choose **Web application**.
6. Set the **Authorized redirect URIs** to `https://google.github.io/android-management-api-samples/oauth_callback.html`.
7. Keep your Client ID and Client Secret handy when running the notebooks.

You can run the notebooks in [Google Colab](https://colab.research.google.com)
using the following links:

*   [quickstart.ipynb](https://colab.research.google.com/github/google/android-management-api-samples/blob/master/notebooks/quickstart.ipynb)
*   [web_apps.ipynb](https://colab.research.google.com/github/google/android-management-api-samples/blob/master/notebooks/web_apps.ipynb)
*   [managed_configurations.ipynb](https://colab.research.google.com/github/google/android-management-api-samples/blob/master/notebooks/managed_configurations.ipynb)
*   [codelab_kiosk.ipynb](https://colab.research.google.com/github/google/android-management-api-samples/blob/master/notebooks/codelab_kiosk.ipynb)
