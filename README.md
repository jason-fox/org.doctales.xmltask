org.jung.xmltask
================

[![license](https://img.shields.io/github/license/stefan-jung/org.jung.xmltask)](http://www.apache.org/licenses/LICENSE-2.0)

**org.jung.xmltask** is an abstract base [DITA-OT Plug-in](https://www.dita-ot.org/plugins) for the [DITA-OT](http://dita-ot.github.io) that provides the [OOPS Consultancy XMLTask](https://github.com/antlibs/ant-xmltask) library. Xmltask provides the facility for automatically editing XML files as part of an Ant build. The plug-in is designed to be extended.


## Installing the Plug-in

Install the plugin using the `dita` command.
```bash
dita --install https://github.com/stefan-jung/org.jung.xmltask/archive/master.zip
```


## Dependency

To define a dependency in your own custom plugin on this plugin, simply add a `<require>` element to your own `plugin.xml`

```xml
<plugin id="com.example.dita">
  <require plugin="org.jung.xmltask"/>
</plugin>
```

---

# License

[Apache 2.0](LICENSE) © 2023 Stefan Jung

The Program includes the following additional software components which were obtained under license:

-   xmltask.jar - https://github.com/antlibs/ant-xmltask - **Apache 1.1 license**
