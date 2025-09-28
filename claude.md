# Claude Instructions for Zendesk Email Theme

```html
<!DOCTYPE html>
<html dir="auto" {{lang}}>
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <style type="text/css">
    table td {
      border-collapse: collapse;
    }
    {{styles}}
  </style>
</head>
<body {{attributes}} style="width: 100%!important; margin: 0; padding: 0;">
  <div style="font-family: 'system-ui','-apple-system','BlinkMacSystemFont','Segoe UI','Roboto','Oxygen-Sans','Ubuntu','Cantarell','Helvetica Neue','Arial','sans-serif'; font-size: 14px; line-height: 1.5; color:#444444;">
    {{content}}
  </div><br/>
  <div style="font-family: 'system-ui','-apple-system','BlinkMacSystemFont','Segoe UI','Roboto','Oxygen-Sans','Ubuntu','Cantarell','Helvetica Neue','Arial','sans-serif'; font-size: 12px; line-height: 1.5; color: #49545c; margin: 10px 0 14px 0; padding-top: 10px;">
    {{footer}} {{footer_link}}
  </div><br/>
  {{quoted_content}}
</body>
</html>
```