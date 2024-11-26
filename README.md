# LAB2
# Interprétation des résultats obtenus
  # Résultats du modèle CNN
  Le modèle CNN atteint une perte de 0.0117 après 5 époques, ce qui indique qu'il s'adapte efficacement aux données d'entraînement.
  Le modèle obtient une précision impressionnante de 98.69% sur le test, ce qui montre qu'il généralise bien.

  # Résultats du modèle Vision Transformer (ViT)
  Le modèle ViT atteint une perte de 1.68 après 5 époques. Cela suggère que le modèle a plus de difficulté à converger par rapport au CNN.
  Le modèle ViT atteint une précision de 74.98%, bien inférieure à celle du CNN.

# Analyse comparative
  # Performance générale
  Le CNN surpasse largement le ViT en termes de précision et de perte. Avec une précision de 98.69%.
  Le ViT semble moins adapté pour des petits datasets comme MNIST.
  
  # Temps d'entraînement
  Le ViT est beaucoup plus long à entraîner que le CNN (près de 6 minutes par époque pour le ViT contre quelques secondes pour le CNN). Cela reflète la complexité accrue des 
  opérations de type self-attention par rapport aux convolutions.

