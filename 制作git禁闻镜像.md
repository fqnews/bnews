# ����Github��Ŀ���񣬲���ʱͬ���ķ���

˵������Ϊ�����������΢�ſ��������α���Ŀ����ַ�������ƹ�ʱ��̫���㣬�����������һ������Ŀ�ľ��񣬵õ�һ���µ���ַ������ʱͬ������������ƹ㡣

1��ע��һ��github.com�˺ţ�����¼��

2���� https://github.com/fqnews/bnews/blob/master/readme.md

3�������Ͻǵ�Fork���ӣ�fork��ɺ�͵õ���һ�����Լ���git���ŵľ�����ַ��

����fork�ľ��񲻻��Զ�����Դ��Ŀ�����£���ô���أ���2�ְ취:

����1��ÿ���ֹ����£����巽����ɾ��fork����Ŀ������forkһ�£��������µ��ˡ�

��������Fork�����Ŀҳ��Ķ���ƫ�ҵ�λ�ã��и�Setting���ӣ����Setting���Ӻ󣬹�����ҳ��ײ����㡰Delete this repository����ť��ɾ��������Fork���ɡ�

����2����ʱ�Զ�ͬ��

����Ҫһ̨<b>ǽ�⣨��Ϊ��ȫ��ԭ��,����ǽ�⣩</b>��Windows���Ի���Linux VPS,��Linux(Debian 10) VPSΪ�������ȣ���ssh�ͻ��˵�¼linux��Ȼ��ִ���������װgit���ߣ�
```
apt update
apt install git
```

�����windows���ԣ��밲װ [Git for Windows](https://git-scm.com/download/win)

Ȼ��ʹ�� SSH ���ӵ���� GitHub�˺�(���� SSH ��Կ�������� GitHub����������ÿ�η���ʱ�ṩ�û��������룬���㶨ʱ����git���ž���)
�ο�: 
https://docs.github.com/cn/github/authenticating-to-github/connecting-to-github-with-ssh

Ȼ�� Linux ������ִ���������һ��һ�����ο���ִ��,ע�⽫your-github-username�������Լ���github�û�������
```
cd /root
git config --global core.autocrlf input
git clone git@github.com:your-github-username/bnews.git
cd bnews
chmod +x syncnews.sh
git remote add upstream https://github.com/fqnews/bnews.git
```

Ȼ�󽫽ű� `/root/bnews/syncnews.sh` �ӵ����linux crontab ���涨ʱִ�м��ɡ�



Windows ���ȴ�Git CMD�����У�����ִ���������
```
git config --global core.autocrlf true
git clone git@github.com:your-github-username/bnews.git
cd bnews
git remote add upstream https://github.com/fqnews/bnews.git
```
��ʱ���ڵ�ǰ��� bnews Ŀ¼�»���һ�� syncnews.bat ����ű������������ű����뵽windows������ƻ�����ʱִ�м��ɡ�


# ��ǽ-��ѧ��������ǽ���ߡ���ǽ�̳���Ŀ�⡣
<ul >
    <li class="Box-row"><strong><a href="https://github.com/bannedbook/fanqiang/wiki/%E7%A6%81%E9%97%BB%E7%BD%91%E5%AE%89%E5%8D%93%E7%BF%BB%E5%A2%99%E6%96%B0%E9%97%BBAPP">��׿��ǽ����APP(FQNews APP)</a></strong></li>
    <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/%E5%AE%89%E5%8D%93%E7%BF%BB%E5%A2%99%E8%BD%AF%E4%BB%B6#JWBrowser">�����������JWBrowser��</a></strong>
        </li>
  <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/%E5%AE%89%E5%8D%93%E7%BF%BB%E5%A2%99%E8%BD%AF%E4%BB%B6">��׿��ǽ���</a></strong>
        </li>  
        <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/Chrome%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85">Chromeһ����ǽ��</a></strong>
        </li>        
        <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/%E7%81%AB%E7%8B%90firefox%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85">���firefoxһ����ǽ��</a></strong>
        </li>
  <li>
      <strong><a href="https://github.com/fqnews/bnews/blob/master/readme.md">�ⷭǽ��ÿ���ȵ����</a></strong>
    </li>
  <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/blob/master/v2ss/%E8%87%AA%E5%BB%BAV2ray%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B.md">�Խ�V2ray��������ǽ�����̳�</a></strong>
        </li>
      <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/blob/master/v2ss/%E8%87%AA%E5%BB%BAShadowsocks%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AE%80%E6%98%8E%E6%95%99%E7%A8%8B.md">�Խ�Shadowsocks��������ǽ�����̳�</a></strong>
        </li>
  <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/%E5%85%8D%E8%B4%B9ss%E8%B4%A6%E5%8F%B7">���ss�˺�</a></strong>
        </li>  
          <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/v2ray%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7">v2ray����˺�</a></strong>
        </li>
        <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/Goflyway%E5%85%8D%E8%B4%B9%E8%B4%A6%E5%8F%B7">Goflyway����˺�</a></strong>
        </li>
          <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/%E8%8B%B9%E6%9E%9C%E7%94%B5%E8%84%91MAC%E7%BF%BB%E5%A2%99">ƻ������MAC��ǽ</a></strong>
        </li>
        <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/iphone%E7%BF%BB%E5%A2%99">iphone��ǽ</a></strong>
        </li>
        <li class="Box-row">
          <strong><a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/TorBrowser%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85">TorBrowserһ����ǽ��</a></strong>
  </li>
</ul>

# ChromeGo - Chromeһ����ǽ��

һ������Goflyway��v2ray��Daze��SSR��Brook��Lightsocks��trojan�����ơ�psiphon��N�෭ǽ���ߵĵ��Է�ǽ�����Ƽ���ǰ������˳�����γ��ԣ������й���ȫ��������ѷ����������ڸ��¡����ڹ������绷�����ӡ�������ͬ��������Ӫ�̲�ͬ�������������ͬ������ʹ��Ч�����в���еĵ����������е��������ʹ�ã��е�ֻ���ü����˾����Ŀ�����ʺ�������绷������Ҫ���Լ������ԡ�

<b>�Ƽ���</b><br>
<a href="https://github.com/killgcd/justmysocks/blob/master/README.md"><img src="https://raw.githubusercontent.com/killgcd/justmysocks/master/images/bwgss.jpg" alt="���߹���ǽ Just My Socks"></a>

<b>����PC��ǽ�����<a class="d-block" href="https://github.com/bannedbook/fanqiang/wiki/Chrome%E4%B8%80%E9%94%AE%E7%BF%BB%E5%A2%99%E5%8C%85">Chromeһ����ǽ��</a></b>�����غ��ChromeGoĿ¼������ǽ�ű���

<b>ʹ�ñ����</b><br>
���������а�װGoogle Chrome �������Ȼ�����ر��������������Զ�����Google Chrome �������ǽ��
���ر���Ŀ�󣬽�ѹ�������벻Ҫ��ѹ���������Ļ�ո��Ŀ¼·�����벻Ҫ����ѹ��ֱ�Ӵ�ѹ���������У�����ѹ����� 
���غ��������Ķ������ʹ�ð���˵����Ȼ��  <b>0.xx-10.xx��ǽ</b> �����γ��ԡ�

<b>��Ȩ����</b><br>
������ַ���������ҵʹ�á�

