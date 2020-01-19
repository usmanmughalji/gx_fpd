By Roker2

## gx_fpd

Need to remove dependencies

| Command                                                   | Patch status (patched or not) |
| :-------------------------------------------------------- | :---------------------------- |
| patchelf --remove-needed libbacktrace.so gx_fpd           | no                            |
| patchelf --remove-needed libunwind.so gx_fpd              | no                            |
| patchelf --remove-needed libkeystore_binder.so gx_fpd     | no                            |
| patchelf --remove-needed libsoftkeymasterdevice.so gx_fpd | no                            |
| patchelf --remove-needed libsoftkeymaster.so gx_fpd       | no                            |
| patchelf --remove-needed libkeymaster_messages.so gx_fpd  | no                            |
