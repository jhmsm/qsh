x7论坛x77论坛bbs享妹论坛寻花论坛(品茶)

AutoCompleteTextView：单个字符提示空间
MutiAutoCompleteView：要设置分割符，多字符提示
XX.setTokenizer(new MutiAutoCompleteTextView.CommaTonkenizer());//用逗号隔开
completion Threshold 指定至少输入几个字符才出现提示
dropDownAnchor指定在哪个View下单出提示
dropDownSelector 提示项被选中的后的背景

prograssbar:进度条
Seekbar :可设置精度拖动条

//滚动条，一般因为空间太多导致太大现实不下。相当于在外面套了一层
<Scollvie>
<LinearLayout>
</LinearLayout>
</Scollvie>

ratingbar星星品分长条
float rating为评分值


imageSwitcher//图片切换，方便于动画效果的切换
switcher.setInAnimation(AnimationUtils.loadAnimation());//进入效果
switcher.setOutAnimation(AnimationUtils.loadAnimation())//出去效果;
