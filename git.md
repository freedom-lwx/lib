git init
git clone username@host:/path/to/repository
git clone /path/to/repository



git add <filename>
git add *

git commit -m "�����ύ��Ϣ"





git push origin master ���͵�Զ�ֿ̲�origin��master��֧
git remote add origin <server> ����һ����Ϊorigin��Զ�ֿ̲�


git checkout -b fetch ����һ������fetch�ķ�֧
git checkout master �л���master��֧

git branch -d fetch ����Ϊfetch�ķ�֧ɾ��
git push origin branch ����Ϊbranch�ķ�֧��������Ϊorigin��Զ�˲ֿ�



������ϲ�
git pull <remote> <branch>��Զ�˸����ҵı��ز������¸Ķ�,�൱�����ҵĹ���Ŀ¼�л�ȡfetch���ϲ�mergeԶ�˵ĸĶ�
git merge <branch> �ϲ�branch��֧���ҵĵ�ǰ��֧

git add <filename> ��merge���������,���⴦���ͻȻ���ֶ�add
git diff <source_branch> <target_branch> �ڸĶ�֮ǰ���Կ���������֧֮�������



�滻���ظĶ�
git checkout -- <filename> ����������˾Ϳ���ʹ��HEAD�е����������滻���ҵĹ���Ŀ¼�е��ļ�����Ȼ����ӵ��������ĸĶ����Լ����ļ�������Ӱ��
git fetch origin 
git reset --hard origin/master �����Ҫ�������ص����иĶ����ύ�����Ե��������ϻ�ȡ���µİ汾�������ط�ָ֧����



ssh -T git@github.com ͨ��������鿴ssh�Ƿ����óɹ�