# Test Results
Python version used: 3.11.0rc1__ | Operating system: _Windows_______ | Date: _30/10/2026_______
| # | Input | Expected result | Actual result | Pass/Fail |
|---|-------|-----------------|---------------|-----------|
| 1 | https://www.example.com/login | No listed warning signs | |Pass |
| 2 | http://192.0.2.10/account | IP address + HTTP | |Pass |
| 3 | http://example.com@sample.invalid/login | @ symbol + HTTP | |Pass |
| 4 | https://a.b.c.d.e.example.invalid/path | Many hostname segments | |Pass |
| 5 | https://xn--example.invalid/ | Punycode-style hostname | |Pass |