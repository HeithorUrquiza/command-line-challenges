# Soluções dos desafios

``P1-(B)``
```bash
tar -xvzf challenges.tar.gz
```

``P2-(B)``
```bash
cd challenges
```

``P3-(B)``
```bash
ls
```

``P4-(B)``
```bash
mkdir foo
```

``P5-(I)``
```bash
mkdir -p foo/bar/1/2/3
```

``P6-(B)``
```bash
rm -r foo
```

``P7-(B)``
```bash
echo "Hello world"
```

``P8-(B)``
```bash
echo "Hello World" > hello.txt
```

``P9-(B)``
```bash
touch empty.txt
```

``P10-(B)``
```bash
rm empty.txt
```

``P11-(I)``
```bash
> empty.txt
```

``P12-(I)``
```bash
echo -n > empty.txt
```

``P13-(B)``
```bash
cp hello.txt goodbye.txt
```

``P14-(B)``
```bash
mv goodbye.txt hello_copy.txt
```

``P15-(I)``
```bash
diff hello.txt hello_copy.txt
```

``P16-(B)``
```bash
cat hello.txt hello_copy.txt > 2_hellos.txt
```

``P17-(B)``
```bash
pwd
```

``P18-(B)``
```bash
ls -l
```

``P19-(B)``
```bash
echo "Some text" >> restricted.txt
```

``P20-(B)``
```bash
./hello_executable
```

``P21-(B)``
```bash
chmod +x challenge_20
./challenge_20
```

``P22-(B)``
```bash
gcc compile_me.c -o compile_me
./compile_me
```

``P23-(A)``
```bash
./redirect > output.txt
```

``P24-(B)``
```bash
date
```

``P25-(B)``
```bash
ps aux
```

``P26-(B)``
```bash
nproc
```

``P27-(B)``
```bash
uname -r
```

``P28-(B)``
```bash
grep -r "You found the needle in the haystack!" bunch_of_files/
```

``P29-(B)``
```bash
head -n 25 people.csv
```

``P30-(B)``
```bash
tail -n 25 people.csv
```

``P31-(I)``
```bash
diff greeting1.txt greeting2.txt
```

``P32-(I)``
```bash
echo "Hello"; sleep 5; echo "world!"
```

``P33-(I)``
```bash
dd if=/dev/zero of=zero_file bs=1M count=1
```

``P34-(I)``
```bash
dd if=/dev/urandom of=random_file bs=1M count=2
```

``P35-(I)``
```bash
wc -l README.txt
```

``P36-(B)``
```bash
tac README.txt
```

``P37-(I)``
```bash
cut -d',' -f2 people.csv
```

``P38-(A)``
```bash
cut -d',' -f2 people.csv | sort | uniq | wc -l
```

``P39-(A)``
```bash
tail -n +2 people.csv | cut -d',' -f2 | sort | uniq | wc -l
```

``P40-(A)``
```bash
awk -F',' 'NR>1 {print $2}' people.csv | sort | uniq | wc -l
```

