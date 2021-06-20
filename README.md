# GF-Debugger

Debugger Of GameFramework

[中文文档](README-zhc.md)

## First Thing

Please take a look [GameFramework](https://github.com/EllanJiang/GameFramework) first.

And thanks to [EllanJiang](https://github.com/EllanJiang).

## Preview

[![Ri0qPO.png](https://z3.ax1x.com/2021/06/20/Ri0qPO.png)](https://imgtu.com/i/Ri0qPO)
[![Ri07a6.png](https://z3.ax1x.com/2021/06/20/Ri07a6.png)](https://imgtu.com/i/Ri07a6)
[![Ri0HIK.png](https://z3.ax1x.com/2021/06/20/Ri0HIK.png)](https://imgtu.com/i/Ri0HIK)
[![Ri0ORe.png](https://z3.ax1x.com/2021/06/20/Ri0ORe.png)](https://imgtu.com/i/Ri0ORe)
[![Ri0LGD.png](https://z3.ax1x.com/2021/06/20/Ri0LGD.png)](https://imgtu.com/i/Ri0LGD)
[![Ri0vMd.png](https://z3.ax1x.com/2021/06/20/Ri0vMd.png)](https://imgtu.com/i/Ri0vMd)
[![Ri0XxH.png](https://z3.ax1x.com/2021/06/20/Ri0XxH.png)](https://imgtu.com/i/Ri0XxH)
[![Ri0xsA.png](https://z3.ax1x.com/2021/06/20/Ri0xsA.png)](https://imgtu.com/i/Ri0xsA)

## Install

### Install via git URL

Requires a version of unity that supports path query parameter for git packages (Unity >= 2019.3.4f1, Unity >= 2020.1a21). 

1. In Unity , Go to Window -> Package Manager -> Add package from git URL

2. **This module depends on the GF-Core , so you need to install GF-Core First.** , use the url  `https://github.com/shaun-he/GF-Core.git` , then click **Add** , and wait for complie finished.

3. Next , use the url `https://github.com/shaun-he/GF-Debugger.git` , then click **Add** ,  wait for complie finished and done !

### Install via disk

1. Go `https://github.com/shaun-he/GF-Core.git` ,  Click the **Green Code** button , then click **Download Zip**.

2. Go `https://github.com/shaun-he/GF-Debugger.git` , Click the **Green Code** button , then click **Download Zip**.

3. Unzip two file somewhere in your disk.

4. In Unity , Go to Window -> Package Manager -> Add package from disk

5. open the **package.json** which in your GF-Core unzip folder.

6. open the **package.json** which in your GF-Debugger unzip folder.

7. Done!

## About Errors

If you see Errors after install GF-EventSystem , that means you didn't install **GF-Core**.

If you still see the Errors , go find **GF.Debugger.asmdef** in your unzip folder , add **GF.Core** and **GF.Runtime** to the **Assembly Definition Reference** list.

And your **GF.Debugger.asmdef** should look like this

![https://z3.ax1x.com/2021/06/19/RiCl3q.png](https://z3.ax1x.com/2021/06/19/RiCl3q.png)

## Usage

Drag **Debugger** prefab in your scene which in Prefabs folder ，then run，you should see the Debugger in game view .
