MarsPhotos
==========



MarsPhotos is a demo app that shows actual images of Mar's surface. These images are
real-life photos from Mars captured by NASA's Mars rovers. The data is stored on a Web server
as a REST web service.  This app demonstrated the use of [Retrofit](https://square.github.io/retrofit/) to make REST requests to the web service, [Moshi](https://github.com/square/moshi) to
handle the deserialization of the returned JSON to Kotlin data objects, and [Coil](https://coil-kt.github.io/coil/) to load images by URL.

The app also leverages [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata), and
[Data Binding](https://developer.android.com/topic/libraries/data-binding/) with binding 
adapters.

![photos](https://user-images.githubusercontent.com/56432777/170825935-cbad6b6d-0403-41c9-8dbe-97ab3c8cb507.jpg)
![loading](https://user-images.githubusercontent.com/56432777/170825944-c4b5d700-92b3-4ccd-984a-d223a155caec.jpg)
![network](https://user-images.githubusercontent.com/56432777/170825956-c8dd33f1-86ee-45fa-ab45-68a3f4f71df1.jpg)


