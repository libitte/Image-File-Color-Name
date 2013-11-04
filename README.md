# NAME

Image::File::Color::Name - It's new $module

# SYNOPSIS

```perl

use Image::File::Color::Name;
use strict;
use warnings;

use Image::File::Color::Name;

my $filename = q{/tmp/lime.jpeg};

my $colorname = Image::File::Color::Name->new();
print $colorname->fetch($filename);


__END__

GREEN

```

# DESCRIPTION

Image::File::Color::Name returns the color name of the image file

# LICENSE

Copyright (C) libitte.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

libitte <nhachi8@gmail.com>
