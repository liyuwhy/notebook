[TOC]

#ǰ�ԣ���Ϥ�����ؼ���ʹ��

* �����ؼ���һЩ����ʹ�ã��кϵ�Դ�룬ԭ�������
* �����̷����֪ʶ ��ɫ������
* ��������,���������÷�����������

***


#�����ؼ�ʹ��
##TextView 

HTML�ַ�������
mTextView.setText(Html.formHtml("<html����>"))
��ԭ��

``` java
Spannable s = new SapnableString(mTextView.getText());
s.setSpan(new BackgroundColor(Color.RED) ,0,3,0); <���һ����flag>
```

TextView

  lineSpacingMultiplier �и�����

##ImageView

ImageView�ļ��ַ�ʽ

ImageButton Ĭ�ϻ�ʹ�ñ���
���Ǿ�Ҫʹ��͸���������串�ǣ� ��λʮ�����Ƶ���ɫ ͸��  �� �� ��
##Button

***
#��������ʹ��
weight ��ʹ��

 ��ʾʣ������ һ����height �� width Ϊ 0 ��Ȼ��ʹ�� weight
