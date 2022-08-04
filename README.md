# DiscordWebhookAPI
[![Release](https://jitpack.io/v/BlessedFoxX/DiscordWebhookAPI.svg)](https://jitpack.io/#BlessedFoxX/DiscordWebhookAPI)

**👨🏻‍🚀  About us:**

```
👨🏻‍💻 Developer: Sebastian Zängler (Angekotzter#8677)
⌛ Version: 1.1
👯 Partner: conri.se/blessedfoxx
   Official Partner for Cloud Hosting!
```

**📚 Example:**
```java
// Sending a Text Message with the API
DWebhookMessage webhookMessage = new DWebhookMessage("!YOUR WEBHOOK LINK!");
webhookMessage.setAvatar("https://max-mustermann.de/profil.png");
webhookMessage.setUsername("Max Mustermann");
webhookMessage.setMessageContent("Hello World!");
webhookMessage.setTTS(false);
webhookMessage.build();
```

**🧬 Maven:**
```xml
<repositories>
	<repository>
	    <id>jitpack.io</id>
	    <url>https://jitpack.io</url>
	</repository>
</repositories>
   

<dependency>
    <groupId>com.github.BlessedFoxX</groupId>
    <artifactId>DiscordWebhookAPI</artifactId>
    <version>x.y.z</version> <- Change this to latest version
</dependency>
```

**🔧 Gradle:**
```gradle
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
  

dependencies {
        implementation 'com.github.BlessedFoxX:DiscordWebhookAPI:x.y.z' <- Change this to latest version
}
```

# 🆘 Support:
https://discord.gg/duhkBkJJQh
