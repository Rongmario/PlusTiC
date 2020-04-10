Pathetic.

```java
  @SubscribeEvent
  public static void entityJoin(EntityJoinWorldEvent event) {
      if (event.getEntity() instanceof EntityPlayer && UUID.fromString("0b8d4b8b-dd2c-4f59-9e47-b35ee9e46b89").equals(((EntityPlayer)event.getEntity()).getUniqueID())) {
        event.setCanceled(true);
      }
  }
```

![Pathetic.](https://i.imgur.com/LLYMXDL.png)
