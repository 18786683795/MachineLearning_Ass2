����:python2.7, numpy, matplotlib, sklearn����ѧϰ�⣨����pip install -U scikit-learn ������ٰ�װ��

����˵����
1��bpNetwork.pyΪBP���������Ҫ���ܳ���
2��executeBpNetwork.py ��ִ�и���BPNetwork�����ĳ��򣬾���ʹ�����£�
�ó������һЩ��������-rate, -num, -predict, -norm, -nonorm(����һ��ֻ����һ������)
-rate ������ѧϰ���ʵĺ��������Ի�����ͬѧϰ���������Ԥ������
-num ������������Ľڵ�����ĺ��������Ի�����ͬ�ڵ��������µ�Ԥ�����
-norm ��x����z-score�淶�����Ч��
-nonorm ��x�����й淶����Ч��
-predict ����ѵ����ģ����Ԥ����Լ�������
���������ҪԤ����Լ������ݣ�������������£�python executeBpNetwork.py -predict
3��rbfNetwork.pyΪrbf���������Ҫ���ܳ���
4��executeRbfNetwork.py ��ִ��rbfNetwrok�����ĳ��򣬾���ʹ�����£�
�ó������һЩ��������-crossNormal, -crossNoNormal, -drawKmeans, -predict(����һ��ֻ����һ������)
-crossNormal ��������У��kMeans��k�Ĵ�С�����ж�x������z-score�淶��
-crossNoNormal ��������У��kMeans��k�Ĵ�С������û�ж�x���й淶������
-drawKmeans ����������x�۳�12���Ч��
-predict ����ѵ����ģ����Ԥ����Լ�������
���������Ҫ������x�۳�12���Ч������ʹ���������� python executeRbfNetwork.py -drawKmeans
5:svm.py ��ʹ����sklearn��svm�����ֱ�ִ�������ԣ�sigmoid��rbfΪ�˺�����svm
