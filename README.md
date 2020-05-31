# Finder-Component

find any file in your project directory.

1.Clone repository 
```
git clone https://github.com/erakashpatel/Finder-Component.git
```

2.composer update
```
composer update
```

3.run php
```
php ./demo OR ./demo

```

4.
Options 1: Find all files :
```
Finder::create()->in(__DIR__); // Changed with your directly where you want to find.
```

Option 2: Find any extension wise any file :
```
$extention_files  = Finder::create()
		->in(__DIR__)
		->name('*.txt'); 
```

Option 3: Find any file have text contains :
```
$contains_files  = Finder::create()
		->in(__DIR__)
		->name('*.txt')
		->contains('{example-key}');
```

Thanks
Akash Patel

