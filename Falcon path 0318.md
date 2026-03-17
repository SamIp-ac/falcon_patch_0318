# Falcon path 0318  
  
Update llm api  
As v8  
  
Update image  
Update system config  
  
Do json template matching task to find out which json template is the best to describe the image content and then fill the image content into the json template. Do not missing any details of the document.  
  
Here is the template choice:  
{template_choices}  
  
If a field has multiple values, separate them with semicolon ';' only (example: '77.00;25,186.00'), do not use '/'. Only return a JSON object with exactly two keys: "template_name" (the chosen template full name) and "filled_template" (the filled json object). Return only valid JSON, nothing else.  
