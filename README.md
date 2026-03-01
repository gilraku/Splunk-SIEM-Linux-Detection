# splunk soc mini project

project ini dibuat untuk latihan dan portfolio sebagai soc analyst.
fokus utama project ini adalah monitoring dan analisis log linux menggunakan splunk enterprise.

## tujuan
- memahami alur kerja soc analyst
- melakukan deteksi dasar dari log authentication linux
- membuat use case dan incident report sederhana tapi realistis

## environment
- os: ubuntu (host utama)
- siem: splunk enterprise (single node)
- log source: /var/log/auth.log dan /var/log/syslog

## scope
- user creation monitoring
- privilege escalation (sudo)
- authentication activity
