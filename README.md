# Install

Create a virtual environment:

    $ pyenv virtualenv 3.6.4 wosmongo

Install all the requirements:

    $ pip install -r requirements.txt

Open the Jupyter notebooks:

    $ jupyter notebook

Or run the example:

    $ cd scripts
    $ python example1.py
    
[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggVERcbkFbT25lIFBUTSBzaXRlXSAtLT5Ce1doZXJlIGlzIGl0J3MgcG9zaXRpb24gaW4gc2VxdWVuY2U_fVxuQiAtLT4gfENsb3NlIHRvIEMgdGVybWludXN8QyhlLmcuICdNJ0VGVFJIQUtMUEQuLi4pXG5CIC0tPiB8SW4gdGhlIG1pZGRsZXxEKGUuZy4gLi4uWVRSU1cnSydMR1RTQS4uLilcbkIgLS0-IHxDbG9zZSB0byBOIHRlcm1pbnVzfEUoZS5nLiAuLi5SRURSVFNLJ04nTUQpXG5DIC0tPiB8RXh0cmFjdHxGW0FkZCB0aGUgc2hvcnQgc2VxdWVuY2UgaW4gYSBmYXN0YSBmaWxlXVxuRCAtLT4gfEV4dHJhY3R8RlxuRSAtLT4gfEV4dHJhY3R8RiIsIm1lcm1haWQiOnsidGhlbWUiOiJuZXV0cmFsIn0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbT25lIFBUTSBzaXRlXSAtLT5Ce1doZXJlIGlzIGl0J3MgcG9zaXRpb24gaW4gc2VxdWVuY2U_fVxuQiAtLT4gfENsb3NlIHRvIEMgdGVybWludXN8QyhlLmcuICdNJ0VGVFJIQUtMUEQuLi4pXG5CIC0tPiB8SW4gdGhlIG1pZGRsZXxEKGUuZy4gLi4uWVRSU1cnSydMR1RTQS4uLilcbkIgLS0-IHxDbG9zZSB0byBOIHRlcm1pbnVzfEUoZS5nLiAuLi5SRURSVFNLJ04nTUQpXG5DIC0tPiB8RXh0cmFjdHxGW0FkZCB0aGUgc2hvcnQgc2VxdWVuY2UgaW4gYSBmYXN0YSBmaWxlXVxuRCAtLT4gfEV4dHJhY3R8RlxuRSAtLT4gfEV4dHJhY3R8RiIsIm1lcm1haWQiOnsidGhlbWUiOiJuZXV0cmFsIn0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)

[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggVERcbkFbU2hvcnQgc2VxdWVuY2UgZmFzdGEgZmlsZV0gLS0-QihSdW4gbG9jYWwgQkxBU1QgYWdhc2ludCBzdWJqZWN0IGRhdGFiYXNlKVxuQiAtLT4gfERpZmZlcmVudCBzZWFyY2ggcGFyYW1ldGVyc3xCXG5CIC0tPiBDW0JMQVNUIHhtbCBvdXRwdXRdXG5DIC0tPiBEW1NlcXVlbmNlIGFsaWdubWVudCBvZiBlYWNoIGhpdF1cbkMgLS0-IEVbU3VtbWFyaXplZCBvdXRwdXQgaW4gYSBjc3YgZmlsZV1cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJuZXV0cmFsIn0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbU2hvcnQgc2VxdWVuY2UgZmFzdGEgZmlsZV0gLS0-QihSdW4gbG9jYWwgQkxBU1QgYWdhc2ludCBzdWJqZWN0IGRhdGFiYXNlKVxuQiAtLT4gfERpZmZlcmVudCBzZWFyY2ggcGFyYW1ldGVyc3xCXG5CIC0tPiBDW0JMQVNUIHhtbCBvdXRwdXRdXG5DIC0tPiBEW1NlcXVlbmNlIGFsaWdubWVudCBvZiBlYWNoIGhpdF1cbkMgLS0-IEVbU3VtbWFyaXplZCBvdXRwdXQgaW4gYSBjc3YgZmlsZV1cbiIsIm1lcm1haWQiOnsidGhlbWUiOiJuZXV0cmFsIn0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)

[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBBW09uZSBwcm90ZWluIGVudHJ5IGluIHN1YmplY3QgZGF0YWJhc2VdIC0tPiB8U2VhcmNoIGFnYWluc3QgQkxBU1Qgb3V0cHV0fEJ7RG9lcyBpdCBoYXZlIHByZWRpY3RlZCBQVE0gc2l0ZT99XG4gICAgQiAtLT58Tm98IEMoS2VlcCB0aGUgb3JpZ2luYWwgcHJvdGVpbiBlbnRyeSlcbiAgICBCIC0tPnxZZXN8IER7RG9lcyB0aGlzIHByZWRpY3RlZCBQVE0gc2l0ZSBleGlzdCBpbiBVbmlwcm90P31cbiAgICBEIC0tPnxOb3wgRVtUaGUgcHJvdGVpbiBoYXMgbm8gUFRNIHNpdGUgcmVjb3JkZWRdXG4gICAgRCAtLT58Tm98IEZbVGhlIHJlY29yZGVkIFBUTSBzaXRlcyBkbyBub3QgaW5jbHVkZSB0aGUgcHJlZGljdGVkIG9uZV1cbiAgICBFIC0tPiBHKEFkZCB0aGUgcHJlZGljdGVkIFBUTSBzaXRlIHRvIHRoZSBlbnRyeSlcbiAgICBGIC0tPiBHXG4gICAgRCAtLT4gfFllc3wgQyhLZWVwIHRoZSBvcmlnaW5hbCBwcm90ZWluIGVudHJ5KVxuICAgIEMgLS0-IEgoQXBwZW5kIHRoZSBwcm90ZWluIGVudHJ5IHRvIGEgbmV3IFVuaXByb3QgeG1sIGZpbGUpXG4gICAgRyAtLT4gSFxuICAgIEggLS0-fE5leHQgZW50cnl8QVxuIiwibWVybWFpZCI6eyJ0aGVtZSI6Im5ldXRyYWwifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBBW09uZSBwcm90ZWluIGVudHJ5IGluIHN1YmplY3QgZGF0YWJhc2VdIC0tPiB8U2VhcmNoIGFnYWluc3QgQkxBU1Qgb3V0cHV0fEJ7RG9lcyBpdCBoYXZlIHByZWRpY3RlZCBQVE0gc2l0ZT99XG4gICAgQiAtLT58Tm98IEMoS2VlcCB0aGUgb3JpZ2luYWwgcHJvdGVpbiBlbnRyeSlcbiAgICBCIC0tPnxZZXN8IER7RG9lcyB0aGlzIHByZWRpY3RlZCBQVE0gc2l0ZSBleGlzdCBpbiBVbmlwcm90P31cbiAgICBEIC0tPnxOb3wgRVtUaGUgcHJvdGVpbiBoYXMgbm8gUFRNIHNpdGUgcmVjb3JkZWRdXG4gICAgRCAtLT58Tm98IEZbVGhlIHJlY29yZGVkIFBUTSBzaXRlcyBkbyBub3QgaW5jbHVkZSB0aGUgcHJlZGljdGVkIG9uZV1cbiAgICBFIC0tPiBHKEFkZCB0aGUgcHJlZGljdGVkIFBUTSBzaXRlIHRvIHRoZSBlbnRyeSlcbiAgICBGIC0tPiBHXG4gICAgRCAtLT4gfFllc3wgQyhLZWVwIHRoZSBvcmlnaW5hbCBwcm90ZWluIGVudHJ5KVxuICAgIEMgLS0-IEgoQXBwZW5kIHRoZSBwcm90ZWluIGVudHJ5IHRvIGEgbmV3IFVuaXByb3QgeG1sIGZpbGUpXG4gICAgRyAtLT4gSFxuICAgIEggLS0-fE5leHQgZW50cnl8QVxuIiwibWVybWFpZCI6eyJ0aGVtZSI6Im5ldXRyYWwifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)
