##ð�������㷨���ӻ�ʵ�֣�
ʵ��˼·����ð�������㷨�����ӳ���ʾ

***

ʵ�ֹ��̣�

***

`
javascript:
var clear = setInterval(fun,time);//�������õķ����������ں���
//��������ʵ�ֵķ���

var i=0,j=0;
var size = ele.length;//��ȡ��Ҫ��������ݳ���
if(i<size){
    if(j<size-i-1){
        (�˴�д �����ж���Ԫ�ؽ������̣���);
        j++;//j+1;
        return;//����һ��ִֹͣ��
    }
    else{//��j����һ���Ժ� i+1
        j = 0;  //��j����Ϊ0
        i++;
    }
    else{//��i������ɣ����Interval
        i = 0��//��ʼ��i;
        clearInterval(fun);
    }
}`
***
