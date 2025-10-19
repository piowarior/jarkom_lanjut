# CATATAN PERT4 JARKOM LANJUT CONTAINER LAB TOPOGRAFI

 ## UNTUK UP NETWORK

```bash 
containerlab deploy -t namafile.yml
```

## UNTUK DOWN NETWORK 
```bash
containerlab destroy -t namafile.yml
```

## UNTUK MAPPING NETWORK 
```bash
containerlab graph -t namafile.yml --srv "127.0.0.1:80"
```

## UNTUK MASUK KE ROUTER 
```bash
docker exec -it clab-namafile-namarouter vtysh
```

## UNTUK MASUK PC
```bash
docker exec - it clab-namafile-namapc sh
```