 
 
�⼸���¶��������вƽ�����Ŀ���вƽ�����ʢ���������£�ʢ��֧ͨ���������޹�˾�����Ƴ��ģ�һ�������ͷ��յ����APP������Ȥ�Ŀ����������棬���治��Ŷ������

�вƽ������ص�ַ��http://8.shengpay.com/ 

ǰ��ʱ�����Ʒ��������һ���������룬��֧�����������������ƣ��������ҷ�����һ����ʵ�ֵķ�ʽ�ɡ�

�ش�д�����demo������һ�»������������ʵ�֣���Ҫ�������������롢У���������룩������Ч��ͼ���£�

![mahua](http://img.blog.csdn.net/20141103170646291?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3VsaWFuZ2h1YW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

![mahua](http://img.blog.csdn.net/20141103170742077?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3VsaWFuZ2h1YW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

![mahua](http://img.blog.csdn.net/20141103170914881?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3VsaWFuZ2h1YW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

![mahua](http://img.blog.csdn.net/20141103172534078?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvd3VsaWFuZ2h1YW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

##�����ṹ

UI��LockIndicator��GestureContentView��
    �������Զ���View���������Ƶĳ��ֺͻ��ƣ����Ǽ̳���ViewGroup�����9��ImageView����ʾͼ��, ��onLayout�����������������ǵ�λ�ã�

    GestureDrawline���������ƻ�����·�����ƣ�����㣬�Լ��м侭����Ļ����߼���������������㶨��

���ݣ�GesturePoint����Ÿ����λ�úͶ�Ӧ���룬����·����������У�������9�����������ϡ�

����У�飺�洢�û����õ��������룬��Ӧ���������У��û�����ҳ��Ļ����������бȶԡ�



##ʵ��˼·

1. ���Ϸ�����ʾ������һ����(LockIndicator.Java)��ʵ�֣��Զ���view������9����ʾͼ�ꣻ
2. �����������������һ����(GestureContentView.java)��ʵ�֣����̳���ViewGroup����, ���9��ImageView����ʾͼ��, ��onLayout�����������������ǵ�λ�ã�
3. ����·�����ƣ� ��һ����(GestureDrawline.java)��ʵ�֣���дonTouchEvent()����������������������TouchEvent�¼�: ACTION_DOWN��ACTION_MOVE��ACTION_UP�¼����������������Ӳ�ͬ��֮���·����
4. 9����Ķ�����һ����(GesturePoint.java)��ʵ�֣���������λ�á�״̬������ͼƬ�������Ϣ��
5. ��������Ļ�ȡ���ж���ָ��ǰ��λ�ã����ݻ���·�������ĵ㣬��˳�򱣴���Ƶĵ��˳��(����ĵ�˳����ϵ��·ֱ��ǣ�1,2,3,4,5,6,7,8,9)���������ظ��ĵ㡣



##����ʵ�ֲ��裺
1.Ҫ��һ��������ʾ��9�����еĵ�һ���㡣���汣���е�ǰ����������ҵĸ���λ�õ�����
2.�Զ���GroupView������װ9���㣬9�������ʾ��ͨ��ImageView����дonLayout����������õ㰴��������
3.����һ�����Ի��ߵ�View����дonTouchEvent���������������������л�ֱ�ߵĲ���
4.�ж��û���ָ��ǰ��λ�ã�ȡ����ǰ��λ��ȥ����9�����е�ÿ�����λ�ý��бȽϣ�����û����λ����ĳһ����֮�ڣ���ô���Ǹ����û�����ͼƬ��



##�����ⷴ��
��ʹ�������κ����⣬��ӭ�������ң�������������ϵ��ʽ���ҽ���

* �ʼ�(mrwujay@163.com)
* blog: http://blog.csdn.net/wulianghuan

