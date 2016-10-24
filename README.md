# input-one-row-and-one-word-each-time
一次读取一行数据给vector或者一个单词给vector的对象
    
    //一次读取一行。
    vector<string> vec;
    ifstream input(fileName);
    string buf;
    getline(input, buf);//input是一个输入流，从input中读取一行并存入buf
    vec.pushback(buf);    //将buf存入vector<string> vec
    
    //一次读取一个单词给buf
    vector<string> vec;
    ifstream input(fileName);
    string buf;
    //用这个
    while(input>>buf)
    vec.pushbace(buf);
    
