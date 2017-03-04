# Xamarin.Forms.WrapLayout

[![NuGet](https://img.shields.io/nuget/v/Xamarin.Forms.WrapLayout.svg)](https://www.nuget.org/packages/Xamarin.Forms.WrapLayout)

Provides a `WrapLayout` for Xamarin.Forms applications.

## How to install

`PM> Install-Package Xamarin.Forms.WrapLayout`

## How to use

```xml
<?xml version="1.0" encoding="utf-8" ?>
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             ...
             xmlns:xf="clr-namespace:Xamarin.Forms;assembly=Xamarin.Forms.WrapLayout"
             ...>

    <!-- WrapLayout example -->
    <xf:WrapLayout Orientation="Horizontal">
        <Label Text="Welcome to Xamarin Forms!" BackgroundColor="Red" />
        <Label Text="Welcome!" BackgroundColor="Yellow" />
        <Label Text="Small label" BackgroundColor="Gray" />
        <Label Text="This is a very loooooong label!" BackgroundColor="Blue" />
    </xf:WrapLayout>
</ContentPage>
```

## Credits

This module has been built by MarkSmith.8123 and originally posted on Xamarin.Forms forums.
https://forums.xamarin.com/discussion/comment/57486/#Comment_57486

Since this code was originally built for Xamarin.Forms 1.0.6186, some of the methods were deprecated and the code have been reviewed to remove this deprecated methods.

All credits goes to the creator: MarkSmith.8123
