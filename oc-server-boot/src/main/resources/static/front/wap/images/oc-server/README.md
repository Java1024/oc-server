<h1 style="text-align: center">EL-ADMIN ��̨����ϵͳ</h1>
<div style="text-align: center">

[![AUR](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg)](https://github.com/elunez/eladmin/blob/master/LICENSE)
[![star](https://gitee.com/elunez/eladmin/badge/star.svg?theme=white)](https://gitee.com/elunez/eladmin)
[![GitHub stars](https://img.shields.io/github/stars/elunez/eladmin.svg?style=social&label=Stars)](https://github.com/elunez/eladmin)
[![GitHub forks](https://img.shields.io/github/forks/elunez/eladmin.svg?style=social&label=Fork)](https://github.com/elunez/eladmin)

</div>

#### ��Ŀ���
һ������ Spring Boot 2.1.0 �� Spring Boot Jpa�� JWT��Spring Security��Redis��Vue��ǰ��˷���ĺ�̨����ϵͳ

**�����ĵ���**  [https://el-admin.vip](https://el-admin.vip)

**�����ַ��**  [https://el-admin.xin](https://el-admin.xin)

**�˺����룺** `admin / 123456`

#### ��ĿԴ��

|     |   ���Դ��  |   ǰ��Դ��  |
|---  |--- | --- |
|  github   |  https://github.com/elunez/eladmin   |  https://github.com/elunez/eladmin-web   |
|  ����   |  https://gitee.com/elunez/eladmin   |  https://gitee.com/elunez/eladmin-web   |

#### ��Ҫ����
- ʹ�����¼���ջ��������Դ�ḻ��
- ��Ч�ʿ�����������������һ������ǰ��˴���
- ֧�������ֵ䣬�ɷ���ض�һЩ״̬���й���
- ֧�ֽӿ�������������������·����ѹ������
- ֧�ֽӿڼ���Ĺ���Ȩ��������Ȩ�ޣ����Զ������
- �Զ���Ȩ��ע���������ӿ�ע�⣬�ɿ��ٶԽӿ����������
- ��һЩ���õ�ǰ�������װ������������������ֵ��
- ǰ���ͳһ�쳣���ش���ͳһ����쳣�����ⷱ�����ж�
- ֧�������û���������������ܼ�أ�֧�����Ƶ��û���¼
- ֧����ά�����ɷ���ض�Զ�̷�������Ӧ�ý��в��������

####  ϵͳ����
- �û������ṩ�û���������ã������û���Ĭ������Ϊ123456
- ��ɫ������Ȩ����˵����з��䣬�ɸ��ݲ������ý�ɫ������Ȩ��
- �˵�������ʵ�ֲ˵���̬·�ɣ���˿����û���֧�ֶ༶�˵�
- ���Ź���������ϵͳ��֯�ܹ������α��չʾ
- ��λ�������ø������ŵ�ְλ
- �ֵ������ά������һЩ�̶������ݣ��磺״̬���Ա��
- ϵͳ��־����¼�û�������־���쳣��־�����㿪����Ա��λ�Ĵ�
- SQL��أ�����druid ������ݿ�������ܣ�Ĭ���û���admin������123456
- ��ʱ��������Quartz����ʱ���񣬼���������־�������������һĿ��Ȼ
- �������ɣ�����������ǰ��˴��룬���ٴ����ظ��Ĺ�������
- �ʼ����ߣ���ϸ��ı�������html��ʽ���ʼ�
- ���ͼ����ʹ��sm.msͼ������������ͼƬ�ϴ�ʹ�ã���ͼ������ô�ȶ�����̫����ʹ��
- ��ţ�ƴ洢����ͬ����ţ�ƴ洢�����ݵ�ϵͳ�������¼��ţ��ֱ�Ӳ���������
- ֧����֧����������֧����֧�������ṩ�˲����˺ţ������в���
- �����أ���ط������ĸ������
- ��ά����һ���������Ӧ��

#### ��Ŀ�ṹ
��Ŀ���ð����ܷ�ģ��Ŀ�����ʽ���ṹ����

- `eladmin-common` Ϊϵͳ�Ĺ���ģ�飬���ֹ����࣬�������ô��ڸ�ģ��

- `eladmin-system` Ϊϵͳ����ģ��Ҳ����Ŀ���ģ�飬Ҳ��������Ҫ��������ģ��

- `eladmin-logging` Ϊϵͳ����־ģ�飬����ģ�������Ҫ��¼��־��Ҫ�����ģ��

- `eladmin-tools` Ϊ����������ģ�飬������ͼ�����ʼ����ƴ洢�����ش洢��֧����

- `eladmin-generator` Ϊϵͳ�Ĵ�������ģ�飬�������ɵ�ģ���� system ģ����

#### ��ϸ�ṹ

```
- eladmin-common ����ģ��
    - annotation Ϊϵͳ�Զ���ע��
    - aspect �Զ���ע�������
    - base �ṩ��Entity��DTO�����mapstruct��ͨ��mapper
    - config �Զ���Ȩ��ʵ�֡�redis���á�swagger���á�Rsa���õ�
    - exception ��Ŀͳһ�쳣�Ĵ���
    - utils ϵͳͨ�ù�����
- eladmin-system ϵͳ����ģ�飨ϵͳ������ڣ�
	- config ���ÿ����뾲̬��Դ��������Ȩ��
	    - thread �̳߳����
	- modules ϵͳ���ģ��(��¼��Ȩ��ϵͳ��ء���ʱ������ά�����)
- eladmin-logging ϵͳ��־ģ��
- eladmin-tools ϵͳ����������ģ��
- eladmin-generator ϵͳ��������ģ��
```
    
#### ϵͳԤ��
<table>
    <tr>
        <td><img src="https://img.el-admin.xin/20200605172248.png"/></td>
        <td><img src="https://img.el-admin.xin/20200605172339.png"/></td>
    </tr>
    <tr>
        <td><img src="https://img.el-admin.xin/20200605172432.png"/></td>
        <td><img src="https://img.el-admin.xin/20200605172455.png"/></td>
    </tr>
    <tr>
        <td><img src="https://img.el-admin.xin/20200605172536.png"/></td>
        <td><img src="https://img.el-admin.xin/20200605172558.png"/></td>
    </tr>
    <tr>
        <td><img src="https://img.el-admin.xin/20200605172645.png"/></td>
        <td><img src="https://img.el-admin.xin/20200605172715.png"/></td>
    </tr>
</table>

#### �ر���л

- ��л [JetBrains](https://www.jetbrains.com/) �ṩ�ķ���ҵ��Դ���������Ȩ

- ��л [PanJiaChen](https://github.com/PanJiaChen/vue-element-admin) �����ṩ��ǰ��ģ��

- ��л [Moxun](https://github.com/moxun1639) �����ṩ��ǰ�� Curd ͨ�����

- ��л [zhy6599](https://gitee.com/zhy6599) �����ṩ�ĺ����ά������ع���

- ��л [j.yao.SUSE](https://github.com/everhopingandwaiting) �����ṩ�������ӿ���Redis�����ȹ���

- ��л [d15801543974](https://github.com/d15801543974) �����ṩ�Ļ���ע���ͨ�ò�ѯ��ʽ

#### ��Ŀ����
��Ŀ�ķ�չ�벻�����֧�֣������ߺȱ����Ȱ�?  [Donate](https://el-admin.vip/donation/)

#### ��������
 - QQȺ: 606173512
