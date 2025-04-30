# 🛡️ IDS and Attack Analysis Project using Snort, Splunk, Wireshark, and iptables

## 👤 By:
Yazan Al-Aranji – SOC Analyst

## 📄 Project Description:
This project demonstrates the design and implementation of a complete Intrusion Detection System (IDS) in a virtual lab environment. It simulates real-world attacks to test detection capabilities, log analysis, and firewall response.

## 🧰 Tools and Technologies:
- **Snort**: Network-based Intrusion Detection System to capture and generate alerts.
- **Splunk**: SIEM platform used for centralized alert monitoring, analysis, and dashboard visualization.
- **Wireshark**: Packet analyzer for traffic inspection and protocol analysis.
- **iptables**: Host-based firewall configured to block detected attacks and simulate real-world response.

## 🧪 Simulated Attacks:
- **SYN Flood Attack using hping3**
- **Nmap XMAS Scan**

> **Note**: Only the SYN Flood attack was analyzed through a full dashboard in Splunk. The Nmap scan was analyzed using logs and filtering but not visualized through dashboard panels.

## 📊 Key Features:
- Complete IDS deployment in a virtual lab using VMware.
- Integration between Snort and Splunk for real-time alert ingestion.
- Wireshark packet-level traffic analysis for both attack scenarios.
- Custom iptables rules to demonstrate response capabilities.
- Dashboard in Splunk showing alert counts, source/destination IPs, and target ports (for SYN Flood).

## 🧠 Learning Outcomes:
- Practical understanding of IDS configuration and detection tuning.
- Hands-on analysis of alerts and attack patterns.
- Firewall configuration and packet flow control.
- Threat visibility and attack profiling using SIEM tools.


---

# 🛡️ مشروع كشف التسلل وتحليل الهجمات باستخدام Snort وSplunk وWireshark وجدار حماية iptables

## 👤 إعداد:
يزن العرنجي – محلل أمن معلومات (SOC Analyst)

## 📄 وصف المشروع:
يتناول هذا المشروع بناء نظام كشف التسلل IDS وتحليل الهجمات في بيئة افتراضية، مع محاكاة واقعية لهجمات شبكة وتحليلها باستخدام أدوات احترافية في مجال أمن المعلومات.

## 🧰 الأدوات المستخدمة:
- **Snort**: لكشف التسللات وتوليد التنبيهات.
- **Splunk**: لمراقبة وتحليل التنبيهات بشكل مركزي باستخدام SIEM.
- **Wireshark**: لتحليل الترافيك على مستوى الحزم.
- **iptables**: لإعداد جدار حماية مضيف واستجابة للهجمات.

## 🧪 الهجمات المحاكاة:
- هجوم SYN Flood باستخدام hping3
- فحص XMAS باستخدام nmap

> **ملاحظة**: تم إنشاء Dashboard فقط لهجوم hping3 داخل Splunk. أما هجوم nmap فتم تحليله عبر التنبيهات بدون إنشاء واجهة Dashboard خاصة به.

## 📊 أهم الإنجازات:
- بناء بيئة افتراضية متكاملة (Ubuntu, Kali, Metasploitable).
- تكامل كامل بين Snort و Splunk لتوثيق التنبيهات.
- تحليل حركة الشبكة باستخدام Wireshark.
- تنفيذ قواعد iptables لمنع الهجمات وتعزيز الأمان.
- إنشاء لوحة تحكم Dashboard تعرض تنبيهات الهجوم وتفاصيله.

## 🧠 الدروس المستفادة:
- إعداد بيئة اختبار متقدمة لأمن الشبكات.
- تحليل تنبيهات الشبكة وفهم الأنماط الهجومية.
- ربط أنظمة IDS بجدران الحماية.
- استخدام أدوات SIEM و packet analysis بفعالية.

