# cas-overlay-template
# Dependencies

- JDK `11`

# Run

To run the project, use:

```bash
# Use 
./gradlew run
```

# Get JWT Token 

To run the project, use:

```bash
# Use 
root@hp:~# curl -k https://sso-hp.com.vn:8444/cas/oauth2.0/token?grant_type=password'&'client_id=exampleOauthClient'&'client_secret=exampleOauthClientSecret'&'username=nhuy'&'password=12345678 | jq
```
#Output
```
{
  "access_token": "eyJ6aXAiOiJERUYiLCJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2IiwiY3R5IjoiSldUIiwidHlwIjoiSldUIiwib3JnLmFwZXJlby5jYXMuc2VydmljZXMuUmVnaXN0ZXJlZFNlcnZpY2UiOiIzIn0..Q_x5I5RBljeMRMDSRVi5Yg.cPdFy2PuYO14SbcrDX31DKpnk7DAJ5kDTjn5u5EcB2dRjstsM1-e1Xe8ileKVbERHx5gSnAhuQhUS-K_4qXDRbEj9mrMcqLm8PtN5yxxQ8usRGsek3TCSWRctRuFEw-dqjHOUPEMTkGDlQqUabVDbs32wPhqA5NDHO10eUdT5_LuMat81BM8nBEouq-fCI8-FViLGn3qwAc_QcDH1uK5EMWy5iHZ4jT7A90fZSuo7ZTlbODhE9k6YvNCAfzvfxqFSwd8V92YfllYm6G2bKNgMWah4mL1_f5aqWeSqInzJ3DA6iKNv0RryK_yGhaqqOEuBTENOoqFbrTJU0GsiVbbWb9LHFPGiXFpgb7PSLcIVwmZzdPveVjDRJaEcu8C_bYyuHb_9wrH0663RcuXUItVeIxxkAh9yqa7FAf5eP8TIKzHAhKG0BHV-ysq_f2nxZ3TxF2GNvjrpmhEp8FzG9DguUFEq-n3r9Csa6gaGhnqc2LCZefQ7DXjFWCuZ2z65caSngD34cF0r7KOQsSadBdPduFEpI9f3guAEvvqU8uujuVl02lMjos7eMBRFIsI3goruLu_K3Exa3-VOxWNAacdiMU2VJYDMkodF3ElVK0QkUbSK8rTLlXbuViM5wt-X00vSlyi2BxdUopilZKuTm1pXxZtbvRqyajeb3a0gZGVzJylCSX7HwJUQZ7ncMCIVLNgfvB1kYMssPqadr1b4GHWCVUECZGgjMk-DasFp-gqvBsDegJ1Vhmdc7pC1cRc6bD3.ZGLbKFNhJMag34Y2xbh26w",
  "refresh_token": "RT-5-Z2LbzVvaEVepCty5Mpv-VQX9zrfBRY8q",
  "token_type": "bearer",
  "expires_in": 28800,
  "scope": ""
}

```
