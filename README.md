# Day-6-assignment-
letsupgrade {
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Day 6 Assignment.ipynb",
      "provenance": [],
      "collapsed_sections": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "metadata": {
        "id": "Gxcprho-3jtq",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "ba257001-3522-4499-8d62-1d6196c80dd7"
      },
      "source": [
        " \n",
        "def Convert(list): \n",
        " \n",
        "    res_dct = {lst[i]: lst[i + 1] for i in range(0, len(lst), 2)} \n",
        " \n",
        "    return res_dct \n",
        " \n",
        "list = ['a', 1, 'b', 2, 'c', 3] \n",
        " \n",
        "print(Convert(list))"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "{'a': 1, 'b': 2, 'c': 3}\n"
          ],
          "name": "stdout"
        }
      ]
    }
  ]
}
