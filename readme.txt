1.���� :git init 
�½�һ��testgit�汾�⡣
��ǰtestgitĿ¼�»����һ��.git��Ŀ¼�����Ŀ¼��Git�����ٹ���汾�ġ�
2.���� git add readme.txt��ӵ��ݴ�������ȥ
3.���� git commit����Git�����ļ��ύ���ֿ⡣
git commit -m 'readme.txt�ύ'

git status���鿴�Ƿ����ļ�δ�ύ

4. ����readme.txt���ݣ�ʹ��git status���鿴�½��������ʾreadme.txt�ļ��ѱ��޸ģ�����δ���ύ���޸ģ�
ʹ��git diff readme.txt���鿴readme.txt�ļ����׸���ʲô����


33333333333333

5. �汾���ˣ�
����һ������Ϊ33333333333333��
�鿴����ʷ��¼��ʹ������ git log �� git log������ʾ���������Զ����ʾ��־��
�汾���˲���������ѵ�ǰ�İ汾���˵���һ���汾������ʹ������2�������һ���ǣ�git reset  -�Chard HEAD^ ��ô���Ҫ���˵����ϸ��汾ֻ���HEAD^ �ĳ� HEAD^^ �Դ����ơ������Ҫ���˵�ǰ100���汾�Ļ���ʹ������ķ����϶������㣬���ǿ���ʹ������ļ�����������git reset  -�Chard HEAD~100 ���ɡ�
ͨ����������ɻ�ȡ���汾�ţ�git reflog  
�ɴ˿�֪����������3333�İ汾���� b597e3b.�������ڿ�������

git reset  -�Chard  b597e3b���ָ���

6. ���Զ�̿� 
��һ�����еı��زֿ���gittest������Ȼ�󣬰ѱ��زֿ���������͵�GitHub�ֿ⡣
(1)git remote add origin https://github.com/Gitxieada/gittest.git

(2)git push -u origin master
�ѱ��ؿ���������͵�Զ�̣�ʹ�� git push���ʵ�����ǰѵ�ǰ��֧master���͵�Զ�̡�

