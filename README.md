# CoolLoginBox
仿ios网易支付app登录注册框，酷炫的登录输入框，点击输入框之后输入框上提示的文字会通过一个动画变换到输入框上方！


项目中如有疑问，请联系 xuancaocom@sina.cn  如果对您有帮助，给个star吧！

![image](https://github.com/xuancao/CoolLoginBox/blob/master/gif/GIF.gif)

主要代码：

             <android.support.design.widget.TextInputLayout
                android:textColorHint="#ffffff"
                android:theme="@style/TextLabel"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                app:counterEnabled="true"
                app:counterMaxLength="10"
                app:counterTextAppearance="@style/CountTextAppearance">
                <EditText
                    android:id="@+id/et_password"
                    android:textSize="13sp"
                    android:textColor="#ffffff"
                    android:hint="@string/password"
                    android:maxLength="10"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:inputType="textPassword"
                    android:background="@drawable/selector_bg_edit_2"
                    android:textCursorDrawable="@drawable/bg_input_cursor_2"
                    android:paddingBottom="2dp"/>
            </android.support.design.widget.TextInputLayout>

博客地址 http://www.jianshu.com/p/edefa6f1b1cd

项目中自定义控件源自：https://github.com/julianraj/ValidatedTextInputLayout


