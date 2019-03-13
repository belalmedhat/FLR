import random;

numtobase = {0:"g", 1:"c",2:"a", 3:"t"};

def generate(len, fname, dir):
    file = open("dataset/" + dir + "/" + fname, "w");
    str = "";
    for i in range(0,len-1):
        num = random.randint(0,3);
        str += numtobase[num];
    file.write(str);

def generate_loop(len):
    for i in range(0, 2000):
        generate(len, "gene"+str(len)+ "_" + str(i + 1), "gene"+str(len));

#main program
#generate_loop(10);
#generate_loop(50);
#generate_loop(100);
#generate_loop(500);
#generate_loop(1000);
#generate_loop(5000);
#generate_loop(10000);
#generate_loop(50000);
#generate_loop(100000);
#generate_loop(500000);
#generate_loop(1000000);
generate_loop(5000000);
