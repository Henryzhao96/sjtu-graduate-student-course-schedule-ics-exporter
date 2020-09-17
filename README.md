# ICS Exporter for SJTU Graduate Student Course Schedule

## Requirement

- Python 3.8 or later
- pip

Run `pip install -r requirements.txt` to install required components.


## Instruction

How to get the `JSESSIONID`:

1. Open and login http://yjs.sjtu.edu.cn/ in web browser.
2. Open DevTools -> Network tab and then reload the page.
3. Locate the very first request after reloading or requests to domain `yjs.sjtu.edu.cn`.
4. Find either `Cookie: JSESSIONID=` or `Set-Cookie: JSESSIONID=`.
5. Copy the text after `JSESSIONID=` till the first semicolon(;).


## Contribution

Pull requests and issues are always welcome.
