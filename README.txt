PHPCoins��Դ���رҽ���ƽ̨ϵͳ

----��������-----

���ر�ת��ת��

Ǯ���Զ�����

����ҳ�ֵ����

���ر�����

ʵʱ�ҵ��б�

ʵʱ�����б�

ʵʱK��ͼ

Google˫����֤

֧��SSL


-----��װ��Ҫ--------

Linux 2.6+��Apache 2.4+��Mysql 5.6+, PHP 5.5+

PDO��չ

GD��չ

Bitcoind 0.8+


-----��װ����---------

Ubuntu��װbitcoind

$ sudo add-apt-repository ppa:bitcoin/bitcoin

$ sudo apt-get update

$ sudo apt-get install bitcoin

���� /usr/share/doc/bitcoind/examples/bitcoin.conf �� HomeĿ¼/.bitcoin/bitcoin.conf

����

testnet = 1  (��������ʽ���ر����磬ֻʹ�ñ��رҲ������磬����������������

server=1    (�Է�������ʽ�������У����û�ע�ᣬת����رҶ���Ҫʹ��bitoind������������Ǯ��)

rpcuser=root   (�û��������õ��û���Ҫ��PHPCoinsĿ¼��config.php�ļ��� btc_user= ��ͬ��

rpcpassword=aaa (���룬���õ�����Ҫ��PHPCoinsĿ¼��config.php�ļ��� btc_password= ��ͬ��

rpcport=18332    (�˿ڣ������������18332����ʽ�������8332�����õ�ֵҪ��PHPCoinsĿ¼��config.php�ļ��� btc_port= ��ͬ��

rpcconnect=127.0.0.1  (���������õ�ֵҪ��PHPCoinsĿ¼��config.php�ļ��� btc_host= ��ͬ��


Apache,PHP,Mysql��װʡ�ԣ���Ҫע�����PHP�İ汾ΪPHP5.5���ϣ���������������



--------Ǯ������-----------

��洢��ʽ�����㹻�����ı��رҵ�ַ�أ��ѵ�ַ���뵽bitcoind������Ŀ¼��ÿ������ע���û�����ӵ�ַ����ȡһ����ַ��Ϊ�û�ת����رҵĵ�ַ


--------PHPCoins��װ--------

����Դ���ϴ���Web��Ŀ¼����ѹ��������Ŀ¼Ȩ��Ϊ����PHP���̶�д������config.php�ļ���Ĳ�����

admin_password Ϊ��̨��¼����

db_user Ϊ���ݿ��û���

db_password Ϊ���ݿ�����

db_name Ϊ���ݿ��� 

db_host Ϊ���ݿ����ڵ�����

btc_protocol Ϊ���رҷ�����bitcoindЭ���ѡ http �� https

btc_user Ϊbitcoind���û���

btc_password Ϊbitcoind������

btc_host Ϊbitcoind���ڵ�����

btc_port Ϊbitcoind�Ķ˿�

text_logo Ϊ����LOGO

site_name Ϊ��վ��

smtp_host ΪSMTP��������

smtp_port ΪSMTP����˿�

smtp_user ΪSMTP�����ʺ�

smtp_password ΪSMTP��������


�½�������д�� db_name ���ݿ⣬�����������վ���Զ���װ����̨�ĵ�ַΪ ����/?admin=1

�����Ҫ���°�װ��ɾ����Ŀ¼�µ�install.lock�ļ�

------------����-----------

����QQȺ���� 53023431









