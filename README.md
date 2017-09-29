# smartloader
Just a simple, caching autoloader, for those days when your aren't
composer-autoloading your entire classes :) 


 ## Usage

 Just include  the smartloader.php file, the only change you should need
 is the variable ```php $classes_root``` set that to point to the root directory
 for your class files, and you are good to go.

 ## Note

 This autoloader caches file paths if APC/APCu is enabled, so it doesn't always transverse 
 the filesystem, thereby speeding things up
