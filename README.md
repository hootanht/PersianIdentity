# Persian Identity Library

![Persian Identity Library](http://uupload.ir/files/rm9s_download.jpg)

PersianIdentity is an opensource library to change your identity error to persian language.

-------------------------

| Target | Branch | Version |
| ------ | ------ | ------ |
| Github | master | v1.0.0 | 


## Persian Identity Public Version
| Target | Branch | Version | Download link | Total downloads | GitHub Actions |
| ------ | ------ | ------ | ------ | ------ | ------ |
| Nuget | master | v1.0.0 | [![NuGet](https://img.shields.io/nuget/v/PersianIdentity.svg)](https://www.nuget.org/packages/PersianIdentity) | [![NuGet downloads](https://img.shields.io/nuget/dt/PersianIdentity.svg)](https://www.nuget.org/packages/PersianIdentity) | <a href="https://github.com/hootanht/PersianIdentity"><img alt="GitHub Actions status" src="https://github.com/hootanht/PersianIdentity/workflows/.NET Core/badge.svg"></a> |



## Cross Platform

| Platform | Supported Version |
| ------ | ------ |
| .NET Framework | 4.6.1 Or Higher|
| .NET Standard | 2.0 Or Higher|
| .NET Core | 2.0 Or Higher|
| Mono | 5.4 Or Higher|
| Xamarin.iOS | 10.14 Or Higher|
| Xamarin.Mac | 3.8 Or Higher|
| Xamarin.Android | 8.0 Or Higher|
| Universal Windows Platform (UWP) | 10.0.16299 Or Higher|
| Unity | 2018.1 Or Higher|


## Code Example
Go to your Startup.cs => ConfigureServices and add AddErrorDescriber<PersianIdentityErrorDescriber>() method to your Identity.
```c#
services.AddIdentity<IdentityUser, IdentityRole>()
                .AddEntityFrameworkStores<AppDbContext>()
                .AddDefaultTokenProviders()
                .AddErrorDescriber<PersianIdentityErrorDescriber>();
```



## Developer [![Twitter Follow](https://img.shields.io/twitter/follow/hootanht?style=social)](https://twitter.com/hootanht)

| Name | Github | Email | Telegram |
| ------ | ------ | ------ | ------ |
| Hootan Hemmati | [@hootanht](https://github.com/hootanht) | [hootanhemmati@outlook.com](mailto:hootanhemmati@outlook.com) | https://t.me/hootanht |
