{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "authorship_tag": "ABX9TyMfuqjRy0Ycn/Yt1cZ6nyg7",
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Togunde/Mart-Sales/blob/main/README.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "**DSN Mart Sales Prediction**\n",
        "\n",
        "A machine learning project for the DSN Bootcamp Qualification Hackathon 2026. The goal is to predict total_sales for different product-store combinations.\n",
        "\n",
        "**Approach**\n",
        "\n",
        "- Explored product and store-level sales patterns\n",
        "- Handled missing and inconsistent values\n",
        "- Engineered features such as avg_price and price_diff_pct\n",
        "- Tested multiple regression models\n",
        "- Used CatBoost to handle categorical features\n",
        "- Averaged predictions from multiple CatBoost models to improve stability\n",
        "\n",
        "**Evaluation**\n",
        "\n",
        "The competition uses Root Mean Squared Error (RMSE), where lower is better.\n",
        "\n",
        "- Local validation RMSE: 1077–1078\n",
        "- Public leaderboard RMSE: ~1069+\n",
        "\n",
        "**Tools**\n",
        "\n",
        "Python · Pandas · NumPy · Scikit-learn · CatBoost · Matplotlib · Seaborn · Jupyter\n",
        "\n",
        "**Key Learning**\n",
        "\n",
        "This project taught me that better performance is not always about adding more features. Understanding the data, testing assumptions, avoiding target leakage, and finding the right combination of features and models made the biggest difference.\n",
        "\n"
      ],
      "metadata": {
        "id": "FPE_Q_NbiMcR"
      }
    }
  ]
}