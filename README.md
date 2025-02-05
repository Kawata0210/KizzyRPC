[![CodeFactor](https://www.codefactor.io/repository/github/dead8309/kizzyrpc/badge)](https://www.codefactor.io/repository/github/dead8309/kizzyrpc) [![](https://jitpack.io/v/dead8309/KizzyRPC.svg)](https://jitpack.io/#dead8309/KizzyRPC)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
![Kotlin](https://img.shields.io/badge/kotlin-%230095D5.svg?style=for-the-badge&logo=kotlin&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
[![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/Naereen/badges/)
[![](https://dcbadge.vercel.app/api/server/vUPc7zzpV5)](https://discord.gg/vUPc7zzpV5)

# KizzyRPC
An android library for customising discord rpc used by my [Apps](https://kizxy.herokuapp.com)

![rpc](https://user-images.githubusercontent.com/68665948/183117335-df349a99-e8ae-4329-8234-698c77550e53.png)


# Usage
>Step 1. Add it in your root build.gradle at the end of repositories:
```gradle
allprojects {
	repositories {
	...
	maven { url 'https://jitpack.io' }
	}
}
```
>Step 2. Add the dependency

```gradle
dependencies {
	       implementation 'com.github.dead8309:KizzyRPC:1.0.5'
	}
```


# Demo
```java

KizzyRPCservice rpc = new KizzyRPCservice(token);//Discord account token
        rpc.setName("hi")
	.setApplicationId("962990036020756480")
        .setDetails("details")
        .setLargeImage("attachments/973256105515974676/983674644823412798/unknown.png")
        .setSmallImage("attachments/973256105515974676/983674644823412798/unknown.png")
        .setState("state")
        .setType(0)
        .setStartTimestamps(System.currentTimeMillis())
        .setButton1("Button1","https://youtu.be/1yVm_M1sKBE")
        .setButton2("Button2","https://youtu.be/1yVm_M1sKBE")
        .setStatus("online")
        .build();
```

![RPC _Demo](https://user-images.githubusercontent.com/68665948/172368963-90697dc2-3d7a-42e6-9511-d1497eadb637.png)

