简单的登录界面
==============
## 主要实现代码
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="horizontal"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="155dp"
            android:orientation="vertical">

            <TextView
                android:id="@+id/textView7"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:gravity="center"
                android:text="登录"
                android:textSize="55dp"
                android:textStyle="bold" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="90dp"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textView5"
                android:layout_width="100dp"
                android:layout_height="match_parent"
                android:gravity="center"
                android:text="账号"
                android:textSize="25dp"
                android:textStyle="bold" />

            <EditText
                android:id="@+id/editTextText9"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:ems="10"
                android:inputType="text"
                android:textSize="20dp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="90dp"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textView6"
                android:layout_width="200dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:gravity="center"
                android:text="密码"
                android:textSize="25dp"
                android:textStyle="bold" />

            <EditText
                android:id="@+id/editTextText11"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:ems="10"
                android:inputType="text"
                android:textSize="20dp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="133dp"
            android:orientation="horizontal">

            <Switch
                android:id="@+id/switch1"
                android:layout_width="wrap_content"
                android:layout_height="70dp"
                android:layout_weight="1"
                android:text="记住密码"
                android:gravity="center"/>

            <Space
                android:layout_width="55dp"
                android:layout_height="60dp"
                android:layout_weight="1" />

            <Button
                android:id="@+id/button2"
                android:layout_width="50dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="忘记密码？"
                android:textSize="10dp"/>

            <Space
                android:layout_width="wrap_content"
                android:layout_height="55dp"
                android:layout_weight="1" />
        </LinearLayout>

    </LinearLayout>
</LinearLayout>
