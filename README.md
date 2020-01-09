![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/1.png)

##              Task : Webmap-that-displays-a-WMS-layer (Google Code In)

1. First Install the GeoServer From This Link http://geoserver.org/release/2.16.x/ and also Use any open data file (e.g. from your cities open data portal or the World Bank portal

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/101.JPG)

2. After Successfully Installation Open **GeoServer**. 

`` This tutorial assumes that GeoServer is running at http://localhost:8080/geoserver/web/``

3. Now the login Interface will be open. Login With **Usernmae : admin** and **Password : geoserver**

And Now GeoServer Screen Will be Open.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/geo.JPG)

4. Now Create a New WorkSpace by navigating to Data >> WorkSpaces.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/12.JPG)

5. Click on **Add new workspace**.

6. You will be prompted to enter a workspace Name and Namespace URI

7. Enter the Name and URI according to your project based work. Here I am using Name : Russia and URI : geoserver.org/Russia and choose default workspace. and it's done.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/1.JPG)

### Note : A workspace name is a identifier describing your project. It must not exceed ten characters or contain spaces. A Namespace URI (Uniform Resource Identifier) can usually be a URL associated with your project with an added trailing identifier indicating the workspace. The Namespace URI filed does not need to resolve to an actual valid web address. 

8. Now Navigate to Store and Add a New Store. It will be redirected and you have to choose the type of data source you wish to configure.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/2.JPG)

**Note : Note that the data sources are extensible, so your list may look slightly different.**

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/3.JPG)

9.Under Vector Data Source Select Shapefile.The New Vector Data Source page will be displaed.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/4.JPG)

10. Under **Basic Store Info** Choose **Workspace** that you have previous created In my case It is **Russia**. Enter **Data Source** as Russia_Map. You can write a description. or leave it blank.

11. Under Connection Parameter Choose the **ShapeFile Location (In which directory is present )** choose the required files.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/5.JPG)

12. Click Save You will be redirected to the **New Layer** page in order to configure the Asia_Russia layer

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/6.JPG)

### Adding New Layer

13. Navigate to the New Layer page, click Publish beside the Asia_Russia layer name. then it will redirected to edit layer page which defines the data and publishing parameters for a layer.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/7.JPG)

14. Generate the layer’s bounding boxes by clicking the **Compute from data** and then **Compute from native bounds** links.

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/8.JPG)

15. Click On Save.

16. Now Navigate to **Layer Preview** and at top your layer **Asia_Russia** will be there. then choose OpenLayer Under **Common Formats**

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/9.JPG)

17. An OpenLayers map will load in a new tab and display the shapefile data with the default line style. You can use this preview map to zoom and pan around the dataset, as well as display the attributes of features.

## Installation of Open Layers

OpenLayers is a high-performance, feature-packed library for creating interactive maps on the web. It can display map tiles, vector data and markers loaded from any source on any web page. OpenLayers has been developed to further the use of geographic information of all kinds. It is completely free, Open Source JavaScript, released under the BSD 2-Clause License.

1. First Install the ol package by ``npm install ol``
2. Create the bundle for the browser by ``npm run build ``
3.Download any IDE (Integrated Development Environment) like Visual Code.
4.You Can Install Visual Code Plugins (For not getting any error) ``Optional``
5.Now Create a New HTML file.
7.Open the html file through Web Browser and see the map.

18. Now Create an html document that will display the **OpenLayers** to display the added layer.

## WMS REFLECTOR

This is a great way to preview options in GeoServer without coding a long URL. The reflector will output PNG (the default), JPEG, PNG 8, and GIF. Also, in cases where you don't want to use GeoWebCache, this is quite useful.

Also It creates an open layers or just reflect the image file.

# Image of the Layer

![](https://github.com/ShivamRai2003/Web-map-that-displays-a-WMS-layer/blob/master/IMAGES/11.JPG)
