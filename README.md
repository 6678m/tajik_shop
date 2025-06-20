from PIL import Image
import matplotlib.pyplot as plt

img = Image.open("tajik_magazin.jpg")  #
plt.imshow(img)
plt.axis('off')
plt.show()
