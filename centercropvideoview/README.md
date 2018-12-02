[![](https://jitpack.io/v/nomtek/NomtekUtills.svg)](https://jitpack.io/#nomtek/NomtekUtills)

# Recycler bucket list (min sdk version - 16 )

<img src="../resources/recycler_bucket.gif" width="250">

### How to use - our [sample](https://github.com/nomtek/NomtekUtills/tree/master/app/src/main/java/com/nomtek/recyclerbucketlist/example)
##### Add CenterCropVideoView to your activity layout.
```xml
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    xmlns:app="http://schemas.android.com/apk/res-auto">

    <ImageView
        android:id="@+id/backActionImageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        style="@style/ToolbarIconImageViewLight"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/ic_arrow_back_black"/>

    <TextView
        android:id="@+id/titleTextView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:gravity="center"
        style="@style/ToolbarTitleBoldWhiteWithBackAction"
        android:text="@string/second_activity_toolbar_title"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"/>


</android.support.constraint.ConstraintLayout>

```

##### License

 Copyright (C) 2006 The Android Open Source Project

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.


 Modifications copyright (C) 2014-2016 sprylab technologies GmbH
 Modifications copyright (C) 2018 Nomtek
```


