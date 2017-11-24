
NavigationTabStrip
==================
Based on <a href="https://github.com/Devlight/NavigationTabBar">Devlight/NavigationTabStrip </a><br/>

Add Strip left-right-padding dimension to enable customize strip width.<br/>

You can set the [app:nts_strip_left_right_padding="30dp"] in xml to change the strip width.<br/>
When this value is bigger than the line width will ignore the setting, use default strip width.<br/>


            <com.gigamole.navigationtabstrip.NavigationTabStrip
                android:id="@+id/nts_top"
                android:layout_width="match_parent"
                android:layout_height="56dp"
                android:layout_gravity="center"
                app:nts_active_color="#42a4d1"
                app:nts_color="#42a4d1"
                app:nts_strip_left_right_padding="30dp"
                app:nts_corners_radius="1dp"
                app:nts_inactive_color="#ff1a1e23"
                app:nts_size="15sp"
                app:nts_titles="@array/titles"
                app:nts_weight="3dp"/>

<br/>
