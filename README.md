CÁC BÀI NÂNG CAO ĐÃ LÀM:

NC1	Bố cục master–detail cho tablet.	Tạo res/layout-sw600dp/activity_main.xml 
có hai khung; trong code kiểm tra findViewById(R.id.detailContainer) != null để biết đang ở bố cục nào.

NC4	Thêm hiệu ứng chuyển Fragment.	ft.setCustomAnimations(R.anim.slide_in, R.anim.fade_out, ...).
