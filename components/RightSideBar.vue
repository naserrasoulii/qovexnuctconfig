<template>
    <div class="vertical-menu">
        <div class="h-100">
            <div class="user-wid text-center py-4">
                <div class="user-img">
                    <img src="assets/images/users/avatar-2.jpg" alt="" class="avatar-md mx-auto rounded-circle">
                </div>
                <div class="mt-3">
                    <a href="#" class="text-dark font-weight-medium font-size-16 line-height-h">جان اسنو</a>
                    <p class="text-body mt-1 mb-0 font-size-13">طراح رابط کاربری</p>
                </div>
            </div>

            <!--- Sidemenu -->
            <div id="sidebar-menu">
                <!-- Left Menu Start -->
                <ul class="metismenu list-unstyled" id="side-menu">
                    <li class="menu-title">منو</li>

                    <li>
                        <a href="javascript:%20void(0);" class="waves-effect">
                            <i class="mdi mdi-airplay"></i><span class="badge badge-pill badge-info float-right">2</span>
                            <span>داشبورد</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="index.html">داشبورد 1</a></li>
                            <li><a href="index-2.html">داشبورد 2</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-flip-horizontal"></i>
                            <span>طرح ها</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="layouts-horizontal.html">افقی</a></li>
                            <li><a href="layouts-compact-sidebar.html">نوار کناری فشرده</a></li>
                            <li><a href="layouts-icon-sidebar.html">نوار کناری آیکن</a></li>
                            <li><a href="layouts-boxed.html">طرح جعبه ای</a></li>
                            <li><a href="layouts-preloader.html">انیمیشن بارگذاری</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="calendar.html" class=" waves-effect">
                            <i class="mdi mdi-calendar-text"></i>
                            <span>تقویم</span>
                        </a>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-inbox-full"></i>
                            <span>ایمیل</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="email-inbox.html">صندوق ورودی</a></li>
                            <li><a href="email-read.html">جزئیات ایمیل</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-calendar-check"></i>
                            <span>وظایف</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="tasks-list.html">لیست وظایف</a></li>
                            <li><a href="tasks-kanban.html">تخته یادداشت ها</a></li>
                            <li><a href="tasks-create.html">ایجاد وظیفه</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-account-circle-outline"></i>
                            <span>صفحات</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="pages-login.html">ورود</a></li>
                            <li><a href="pages-register.html">ثبت نام</a></li>
                            <li><a href="pages-recoverpw.html">بازیابی رمز عبور</a></li>
                            <li><a href="pages-lock-screen.html">قفل صفحه</a></li>
                            <li><a href="pages-starter.html">صفحه شروع</a></li>
                            <li><a href="pages-invoice.html">صورتحساب</a></li>
                            <li><a href="pages-profile.html">پروفایل</a></li>
                            <li><a href="pages-maintenance.html">تعمیرات</a></li>
                            <li><a href="pages-comingsoon.html">به زودی</a></li>
                            <li><a href="pages-timeline.html">خط زمانی</a></li>
                            <li><a href="pages-faqs.html">سوالات متداول</a></li>
                            <li><a href="pages-pricing.html">قیمت ها</a></li>
                            <li><a href="pages-404.html">خطای 404</a></li>
                            <li><a href="pages-500.html">خطای 500</a></li>
                        </ul>
                    </li>

                    <li class="menu-title">اجزاء</li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-checkbox-multiple-blank-outline"></i>
                            <span>رابط کاربری</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="ui-alerts.html">اعلان‌ها</a></li>
                            <li><a href="ui-buttons.html">دکمه ها</a></li>
                            <li><a href="ui-cards.html">کارت ها</a></li>
                            <li><a href="ui-carousel.html">گردونه</a></li>
                            <li><a href="ui-dropdowns.html">منوی کشویی</a></li>
                            <li><a href="ui-grid.html">توری</a></li>
                            <li><a href="ui-images.html">تصاویر</a></li>
                            <li><a href="ui-lightbox.html">لایت باکس</a></li>
                            <li><a href="ui-modals.html">مودال ها</a></li>
                            <li><a href="ui-rangeslider.html">انتخاب‌گر بازه</a></li>
                            <li><a href="ui-session-timeout.html">محدودیت زمان جلسه</a></li>
                            <li><a href="ui-progressbars.html">نوارهای پیشرفت</a></li>
                            <li><a href="ui-sweet-alert.html">هشدار Sweet Alert</a></li>
                            <li><a href="ui-tabs-accordions.html">تب و منوی باز شونده</a></li>
                            <li><a href="ui-typography.html">تایپوگرافی</a></li>
                            <li><a href="ui-video.html">ویدئو</a></li>
                            <li><a href="ui-general.html">عمومی</a></li>
                            <li><a href="ui-colors.html">رنگ ها</a></li>
                            <li><a href="ui-rating.html">امتیاز</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="waves-effect">
                            <i class="mdi mdi-newspaper"></i>
                            <span class="badge badge-pill badge-danger float-right">6</span>
                            <span>فرم ها</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="form-elements.html">عناصر فرم</a></li>
                            <li><a href="form-validation.html">اعتبارسنجی فرم</a></li>
                            <li><a href="form-advanced.html">فرم پیشرفته</a></li>
                            <li><a href="form-editors.html">ویرایشگر متن</a></li>
                            <li><a href="form-uploads.html">ارسال فایل</a></li>
                            <li><a href="form-xeditable.html">ویرایشگر Xeditable</a></li>
                            <li><a href="form-repeater.html">تکرار شونده ها</a></li>
                            <li><a href="form-wizard.html">فرم مرحله ای</a></li>
                            <li><a href="form-mask.html">ماسک فرم</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-clipboard-list-outline"></i>
                            <span>جدول ها</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="tables-basic.html">جدول‌های پایه</a></li>
                            <li><a href="tables-datatable.html">جدول های داده</a></li>
                            <li><a href="tables-responsive.html">جدول واکنشگرا</a></li>
                            <li><a href="tables-editable.html">جدول قابل ویرایش</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-chart-donut"></i>
                            <span>نمودار ها</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="charts-apex.html">نمودار Apex</a></li>
                            <li><a href="charts-chartjs.html">نمودار Chartjs</a></li>
                            <li><a href="charts-flot.html">نمودار Flot</a></li>
                            <li><a href="charts-knob.html">نمودار Jquery Knob</a></li>
                            <li><a href="charts-sparkline.html">نمودار Sparkline</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-emoticon-happy-outline"></i>
                            <span>آیکن‌ها</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="icons-boxicons.html">Boxicons</a></li>
                            <li><a href="icons-materialdesign.html">Material Design</a></li>
                            <li><a href="icons-dripicons.html">Dripicons</a></li>
                            <li><a href="icons-fontawesome.html">Font awesome</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-map-marker-outline"></i>
                            <span>نقشه‌ها</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="false">
                            <li><a href="maps-google.html">نقشه گوگل</a></li>
                            <li><a href="maps-vector.html">نقشه وکتور</a></li>
                        </ul>
                    </li>

                    <li>
                        <a href="javascript:%20void(0);" class="has-arrow waves-effect">
                            <i class="mdi mdi-file-tree"></i>
                            <span>چند سطحی</span>
                        </a>
                        <ul class="sub-menu" aria-expanded="true">
                            <li><a href="javascript:%20void(0);">سطح 1.1</a></li>
                            <li><a href="javascript:%20void(0);" class="has-arrow">سطح 1.2</a>
                                <ul class="sub-menu" aria-expanded="true">
                                    <li><a href="javascript:%20void(0);">سطح 2.1</a></li>
                                    <li><a href="javascript:%20void(0);">سطح 2.2</a></li>
                                </ul>
                            </li>
                        </ul>
                    </li>

                </ul>
            </div>
            <!-- Sidebar -->
        </div>
    </div>
</template>