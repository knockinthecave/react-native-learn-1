## ERROR REPORT

### 1. EACESS: permission denied
.expo 디렉토리에 대한 권한이 없어서 발생하는 오류.
디렉토리의 권한을 수정해야한다.

```
sudo chown -R $(whoami) ~/.expo
```

```
chmod -R u+rwx ~/.expo
```