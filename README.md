# MatrixVideoView
A smart VideoView build in java. Who support a full screen video player.
and a Beautiful Ui design.

<h1>How to Use</h1>

1st download this repo and unzip the code then copy the file and paste in below Your project app file.
after pasting the file open your app level build.gradel file and implement the project in them.

<h2>now open your layout where you want to use VideoView. and Use this code</h2>

<LinearLayout
android:id="@+id/video_layout_linear"
android:layout_width="match_parent"
android:layout_height="wrap_content" >

<FrameLayout
android:id="@+id/video_layout"
android:layout_width="fill_parent"
android:layout_height="0dp"
android:layout_weight="2"
android:background="@android:color/black" >

<matrixcri.in.videoview.MatrixVideoView
android:id="@+id/videoView"
android:layout_width="fill_parent"
android:layout_height="fill_parent"
android:layout_gravity="center"
app:matrix_video_fitXY="false"
app:mv_autoRotation="true" />

<matrixcri.in.videoview.MatrixMediaController
android:id="@+id/media_controller"
android:layout_width="fill_parent"
android:layout_height="fill_parent"
app:mv_scalable="true" />
</FrameLayout>
</LinearLayout>
