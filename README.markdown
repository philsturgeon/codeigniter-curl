CodeIgniter-cURL
================

CodeIgniter-cURL is a CodeIgniter library which makes it easy to do simple cURL requests 
and makes more complicated cURL requests easier too.


Requirements
------------

1. PHP 5.1+
2. CodeIgniter 1.7.x - 2.0-dev
3. PHP 5 (configured with cURL enabled)
4. libcurl

Usage
-----

	echo $this->curl->simple_get('http://example.com/');
	echo $this->curl->simple_post('curl_test/message', array('message'=>'Sup buddy'));

For more up to date usage and in-depth examples check the CodeIgniter wiki page:

http://codeigniter.com/wiki/Curl_library/