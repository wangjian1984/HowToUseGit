��ƪ�̳��治��https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374829472990293f16b45df14f35b94b3e8a026220c5000

�鿴����
$ cat ~/.ssh/id_rsa.pub


$ mkdir learngit
$ cd learngit
$ pwd
$ git init   //��ʱ�����һ������Ŀ¼.git�����ڹ���Ŀ¼learngit��
����readme.txg���д�㶫��
$ git add readme.txt    //git add readme.txt�п������ύ�����ļ�
$ git commit -m "��ע"
$ git status  //�鿴���Ķ����ļ��嵥
$ git diff readme.txt   //�޸�����
$ git add readme.txt  //�ٴ�����޸ĺ���ļ�
$ git log //�鿴�汾���޸���ʷ
$ git reset //hard HEAD^ ������һ���汾 HEAD~100 ����n���汾
$ git reset //hard 1094a ����ĳ���ض��汾��������id���ɼ�д
$ git reflog  //�鿴��������
$ git checkout -- readme.txt //�Թ��������ļ��޸Ľ��г���
$ git reset HEAD readme.txt //�Ի��������ļ��޸Ľ��г���
$ rm test.txt //ɾ���ļ����ֶ�ɾ��Ҳһ��
$ git rm test.txt //ɾ�����ύɾ����������
$ git checkout -- test.txt //ɾ���ļ����Իָ�
git remote add origin https://github.com/wangjian1984/HowToUseGit.git  //���ӵ�github
$ git push -u origin master  //��һ���ύ����
$ git push origin master //�ύ����
git remote �鿴Զ�̷�֧
git remote -v ͬ��
--------------------------------------------------------
$ git branch dev ������ֽdev
$ git checkout dev �л���֧
$ git branch �鿴���з�֧
$ git add readme.txt �ڷ�֧���ύ
$ git commit -m "branch test"
$ git checkout master �л�������
$ git merge dev �ϲ���֧����
$ git branch -d dev ɾ����֧
cat readme.txt �������֧�г�ͻʱ�Ƚ�
$ git checkout -b dev origin/dev ���˿�������Զ�̷�֧������,�������ڿ����̳�