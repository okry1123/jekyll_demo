##Title

+ test1
	- test2
	- test3
	- test4
+ test2
	- code

```
        if (mUseBottomSheet) {
            if (mBottomSheetLayout == null) {
                mBottomSheetLayout = (BottomSheetLayout) View.inflate(this, R.layout.base_bottom_sheet, null);
            } else {
                mBottomSheetLayout.removeAllViews();
            }
            View.inflate(this, layoutResID, mBottomSheetLayout);
            super.setContentView(mBottomSheetLayout);
        } else {
            super.setContentView(layoutResID);
        }