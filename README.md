# Bank-bin
 
 ```
 use dy7338\Bank_bin\Bank;

 $result = Bank::matchCard ('6212264301003495221');

 var_dump ($result);
 
 
 array(3) {
  ["status"]=>
  bool(true)
  ["data"]=>
  array(4) {
    ["cardType"]=>
    string(2) "DC"
    ["bank"]=>
    string(4) "ICBC"
    ["bankName"]=>
    string(18) "中国工商银行"
    ["cardNo"]=>
    string(19) "6212264301003495221"
  }
  ["msg"]=>
  string(0) ""
}
