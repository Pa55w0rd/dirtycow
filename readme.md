## dirtycow

脏牛（Dirty Cow）是Linux内核的一个提权漏洞，攻击者可以利用这个漏洞获取root权限。之所以叫Dirty Cow，因为这个漏洞利用了Linux的copy-on-write机制。脏牛的CVE编号是CVE-2016-5195。

脏牛的影响范围很大，几乎涵盖了主流的Linux发行版。Linux内核>=2.6.22（2007年发行）开始就受影响了，直到2016年10月18日才修复

几乎是内核通杀提权漏洞，收藏

