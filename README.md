
# Reto_4

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2FFakerPachanguero%2FReto_4/main?labpath=nb_Repo_4.ipynb)

{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": [],
      "toc_visible": true,
      "authorship_tag": "ABX9TyPVbM2NZ0ZTspoB1TA6wWi/",
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
        "<a href=\"https://colab.research.google.com/github/FakerPachanguero/Reto_4/blob/main/nb_Reto_4.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "# <div style=\"color: #FF5733;\">Repo N° 3</div>"
      ],
      "metadata": {
        "id": "8jtuecDu1Imz"
      }
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "o0W9BKNzZJrK",
        "outputId": "0e84cc80-7b14-4051-eece-7b27a8d46074"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Escribe un Número Entero: 8\n",
            "8 ,no es una letra minuscula en codigo ASCII\n"
          ]
        }
      ],
      "source": [
        "n : int\n",
        "n = int(input(\"Escribe un Número Entero: \"))\n",
        "\n",
        "if n >= 97 and n <= 122:\n",
        "    print( n, \", Representa la letra minúscula: \", chr(n), \" en codigo ASCII\" )\n",
        "\n",
        "else:\n",
        "    print(n,\",no es una letra minuscula en codigo ASCII\")"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "n : str\n",
        "n = str(input(\"Escribe un carácter cualquiera: \"))\n",
        "\n",
        "\n",
        "if  ord(n[0]) % 2 == 0:\n",
        "\n",
        "    print(\"El carácter: \", n[0], \" Representa un número par en codigo ASCII\")\n",
        "\n",
        "else:\n",
        "    print(\"El carácter: \", n[0], \" NO representa un número par en codigo ASCII\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "on7jdwCyet-2",
        "outputId": "4b60698a-817c-495e-8db4-b6793ac471a4"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Escribe un carácter cualquiera: L\n",
            "El carácter:  L  Representa un número par en codigo ASCII\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "n : str\n",
        "n = str(input(\"Escribe un carácter cualquiera: \"))\n",
        "\n",
        "\n",
        "if  ord(n[0]) >= 48 and ord(n[0]) <= 57:\n",
        "\n",
        "    print(\"El carácter: \", n[0], \" Representa un didito en codigo ASCII\")\n",
        "\n",
        "else:\n",
        "    print(\"El carácter: \", n[0], \" NO representa un digito par en codigo ASCII\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "3Y8auv76fFDX",
        "outputId": "10402efb-cb77-45cc-86ef-6dd411cc79f7"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Escribe un carácter cualquiera: 8\n",
            "El carácter:  8  Representa un didito en codigo ASCII\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "n : int\n",
        "n = int(input(\"Escribe un Número natual: \"))\n",
        "\n",
        "if n > 0:\n",
        "   print(\"El número: \",f'\\'{n}\\'', \" es Positivo\" )\n",
        "elif n == 0:\n",
        "    print(\"El número: \",f'\\'{n}\\'', \" es el neutro para la suma\" )\n",
        "elif n < 0:\n",
        "    print(\"El número: \",f'\\'{n}\\'', \", es negativo\" )"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "YQvGixx-pTrT",
        "outputId": "beceb23b-d1a5-4b93-a7fe-78db560b468e"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Escribe un Número natual: 7\n",
            "El número:  '7'  es Positivo\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "#* VARIABLES\n",
        "\n",
        "# Distancia del centro de la circuferencia y la coordenada del punto.\n",
        "d : int = 0\n",
        "\n",
        "# Radio de la circuferencia\n",
        "r = int(input(\"Escribe el radio de la circuferencia: \"))\n",
        "\n",
        "# Coordenadas del centro de la circuferencia\n",
        "# k = a la corrdenada x ; h = a la coordenda y\n",
        "h : float = float(input(\"Escribe la coordenada x, de la circuferencia: \"))\n",
        "k : float = float(input(\"Escribe la coordenada y, de la circuferencia: \"))\n",
        "\n",
        "# Coordenadas del punto\n",
        "x : float = float(input(\"Escribe la coordenada x, del punto: \"))\n",
        "y : float = float(input(\"Escribe la coordenada y, del punto: \"))\n",
        "\n",
        "\n",
        "#* CODE\n",
        "# Fórmula: calculo de la distancia entre dos puntos, de la forma euclidiana\n",
        "d = (((x-h)**2)+((y-k)**2))**0.5\n",
        "\n",
        "if d <= r:\n",
        "    print(\"El punto esta dentro de la circuferencia\")\n",
        "else:\n",
        "    print(\"El punto NO se encuntra dentro de la circuferencia\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "XmXue9_etgOl",
        "outputId": "4d60bf96-b6c9-48e8-cc19-3fc1073d000f"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Escribe el radio de la circuferencia: 8\n",
            "Escribe la coordenada x, de la circuferencia: 0\n",
            "Escribe la coordenada y, de la circuferencia: 0\n",
            "Escribe la coordenada x, del punto: 8\n",
            "Escribe la coordenada y, del punto: 0\n",
            "El punto esta dentro de la circuferencia\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "\n",
        "#VARIABLES\n",
        "edge_a : float = float(input(\"Longitud del lado a: \"))\n",
        "edge_b : float = float(input(\"Longitud del lado b: \"))\n",
        "edge_c : float = float(input(\"Longitud del lado c: \"))\n",
        "\n",
        "t : bool = True\n",
        "\n",
        "\n",
        "#CODE\n",
        "t = edge_a + edge_b > edge_c\n",
        "\n",
        "if t == True:\n",
        "    edge_a + edge_c > edge_b\n",
        "\n",
        "    if t == True:\n",
        "        t = edge_b + edge_c > edge_a\n",
        "\n",
        "        if t == True:\n",
        "            print(\"Se puede formar un triangulo con los lados proporcionados\")\n",
        "        else:\n",
        "            print(\"No se puede formar un triangulo con las medidas dadas\")\n",
        "\n",
        "else:\n",
        "    print(\"No se puede formar un triangulo con las medidas dadas\")"
      ],
      "metadata": {
        "id": "Qs8JyB54pMSZ",
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "outputId": "b7f90a59-727e-489d-83dd-78d1de6da166"
      },
      "execution_count": 1,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Longitud del lado a: 8\n",
            "Longitud del lado b: 7\n",
            "Longitud del lado c: 9\n",
            "Se puede formar un triangulo con los lados proporcionados\n"
          ]
        }
      ]
    }
  ]
}
