echo -n '{"version": "1.1", "host": "example.org", "short_message": "A short message", "level": 5, "some_info": "userXX"}' | nc -w1 -u GRAYLOG_IP 122XX
