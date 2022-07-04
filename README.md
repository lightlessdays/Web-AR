# Web AR: Displaying 3D Models on your browser
![banner](https://raw.githubusercontent.com/lightlessdays/remotehost/main/galaxyshooter2d/Your%20paragraph%20text.png)

Web AR Repository allows you to render your 3D GLB models straight in your browser. To render your own models, follow the steps-

1. Fork/Clone this repository.
2. Upload your .glb or .usdz model in your github repo.
3. In index.html file, on line 22, you will notice the following lines-
```
<model-viewer src="Astronaut.glb"                  
ios-src="Astronaut.usdz"
```
4. Replace Astronaut.glb / Astronaut.usdz with name of your own .glb / .usdz model.
5. Publish your website on GitHub Pages.

For detailed tutorial, [click here](https://medium.com/@lightlessdays/how-to-create-and-deploy-your-own-webar-within-5-minutes-4aa2e0278b81).