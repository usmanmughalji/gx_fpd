I followed following steps which instructed by Roker2 and Patched gx_fpd file for Santoni

By Roker2

## gx_fpd

Need to remove dependencies

| Command                                                   | Patch status (patched or not) |
| :-------------------------------------------------------- | :---------------------------- |
| patchelf --remove-needed libbacktrace.so gx_fpd           | yes                           |
| patchelf --remove-needed libunwind.so gx_fpd              | yes                           |
| patchelf --remove-needed libkeystore_binder.so gx_fpd     | yes                           |
| patchelf --remove-needed libsoftkeymasterdevice.so gx_fpd | yes                           |
| patchelf --remove-needed libsoftkeymaster.so gx_fpd       | yes                           |
| patchelf --remove-needed libkeymaster_messages.so gx_fpd  | yes                           |
