# Codeigniter Smarty
A quick starter code for developer who want to use Codeigniter with Smarty Template Engine

### Version
- CodeIgniter: 3.0.0
- Smarty: 3.1.27

### Usage

Create your template under the folder
```path
application/views/templates/
```

In your controller, instead of rendering view using 
```php
$this->load->view('your_template');
```
use the custom View Library
```php
$this->view->render('your_template.tpl');
```
