# Table of contents

* [Hi6 Robot Controller Function Manual - Robot Language HRScript](README.md)
* [1. Overview](intro/README.md)
  * [1.1 Introduction of HRScript](intro/hrscript.md)
* [2. Basic Syntax](basic-syntax/README.md)
  * [2.1 Statements](basic-syntax/statements.md)
  * [2.2 Identifiers](basic-syntax/identifier.md)
  * [2.3 Types of Statements](basic-syntax/statement-type/README.md)
    * [2.3.1 Procedures](basic-syntax/statement-type/procedure.md)
    * [2.3.2 Assignment Statements](basic-syntax/statement-type/assignment.md)
    * [2.3.3 Comment Statements](basic-syntax/statement-type/comment.md)
    * [2.3.4 Labels](basic-syntax/statement-type/label.md)
  * [2.4 First Program – Hello, World!](basic-syntax/hello-world.md)
  * [2.5 Data Type](basic-syntax/type/README.md)
    * [2.5.1 String Data Type](basic-syntax/type/type-string.md)
    * [2.5.2 Number Data Type](basic-syntax/type/number-type.md)
    * [2.5.3 Boolean Data Type](basic-syntax/type/bool-type.md)
    * [2.5.4 Array Type and Object Type](basic-syntax/type/array-object-type.md)
  * [2.6 Variables](basic-syntax/variable.md)
  * [2.7 Binary and Hexadecimal](basic-syntax/binary-hex-number.md)
  * [2.8 Operators and Expressions](basic-syntax/operator-expression.md)
  * [2.9 Functions](basic-syntax/function/README.md)
    * [2.9.1 Math Functions](basic-syntax/function/func-math.md)
    * [2.9.2 String Functions](basic-syntax/function/func-string.md)
    * [2.9.3 Date and Time Functions](basic-syntax/function/func-datetime.md)
    * [2.9.4 Constructor Functions](basic-syntax/function/func-creator.md)
    * [2.9.5 Other Functions](basic-syntax/function/func-etc.md)
* [3. Flow-Control Statements and Sub-Program](flowcontrol-subprogram/README.md)
  * [3.1 Address](flowcontrol-subprogram/address.md)
  * [3.2 Stop or Wait Statement](flowcontrol-subprogram/stop-wait/README.md)
    * [3.2.1 stop](flowcontrol-subprogram/stop-wait/stop.md)
    * [3.2.2 end](flowcontrol-subprogram/stop-wait/end.md)
    * [3.2.3 delay](flowcontrol-subprogram/stop-wait/delay.md)
    * [3.2.4 wait](flowcontrol-subprogram/stop-wait/wait.md)
  * [3.3 Branch Statement](flowcontrol-subprogram/branch/README.md)
    * [3.3.1 goto](flowcontrol-subprogram/branch/goto.md)
  * [3.4 Conditional Statements](flowcontrol-subprogram/conditional/README.md)
    * [3.4.1 Single-Line if](flowcontrol-subprogram/conditional/simple-if.md)
    * [3.4.2 if-endif](flowcontrol-subprogram/conditional/if-endif.md)
    * [3.4.3 if-else-endif Statement](flowcontrol-subprogram/conditional/if-else-endif.md)
    * [3.4.4. if-elseif-else-endif](flowcontrol-subprogram/conditional/if-elseif-else-endif.md)
    * [3.4.5 switch-case-break-end\_switch](flowcontrol-subprogram/conditional/switch-case-break-end_switch.md)
  * [3.5. Nested Flow-Control Statements](flowcontrol-subprogram/nested-flow-control.md)
  * [3.6 Loop Statements](flowcontrol-subprogram/loop/README.md)
    * [3.6.1 for-next](flowcontrol-subprogram/loop/for-next.md)
  * [3.7 Call, Jump Statement and Subprograms](flowcontrol-subprogram/call-jump/README.md)
    * [3.7.1 call](flowcontrol-subprogram/call-jump/call.md)
    * [3.7.2 Parameters and param, return](flowcontrol-subprogram/call-jump/param-return.md)
    * [3.7.3 jump](flowcontrol-subprogram/call-jump/jump.md)
  * [3.8 Local Variables and Global Variables](flowcontrol-subprogram/local-global-var/README.md)
    * [3.8.1 Local Variables](flowcontrol-subprogram/local-global-var/local-variables.md)
    * [3.8.2 Global Variables](flowcontrol-subprogram/local-global-var/global-variables.md)
    * [3.8.3 Precedence](flowcontrol-subprogram/local-global-var/precedence.md)
* [4. Arrays and Objects](array-object/README.md)
  * [4.1 Arrays](array-object/array/README.md)
    * [4.1.1 Arrays](array-object/array/1d-array.md)
    * [4.1.2 Multidimensional Arrays](array-object/array/md-array.md)
    * [4.1.3 Array Constructor Function](array-object/array/array-creator.md)
  * [4.2 Object](array-object/object.md)
  * [4.3 Copied assignment of arrays and objects](array-object/array-object-assignment.md)
  * [4.4 Call-by-reference and call-by-value](array-object/call-by-reference-call-by-value.md)
* [5. Moving a Robotwith Robot Language](moving-robot/README.md)
  * [5.1 Pose](moving-robot/pose.md)
  * [5.2 Shift](moving-robot/shift.md)
  * [5.3 Pose Expression](moving-robot/pose-expression.md)
  * [5.4 move](moving-robot/move.md)
  * [5.5 User Coordinate System \(UCS\)](moving-robot/ucs.md)
* [6. Communicating with External Devices](external-comm/README.md)
  * [6.1 FB Object: Digital I/O](external-comm/fb-io/README.md)
    * [6.1.1 Input/Output Variables](external-comm/fb-io/io-val.md)
    * [6.1.2 Examples](external-comm/fb-io/io-example.md)
  * [6.2    ENet Module: Ethernet TCP/UDP Communication](external-comm/enet-tcp-udp/README.md)
    * [6.2.1 Constructor](external-comm/enet-tcp-udp/enet-creator.md)
    * [6.2.2 Member Variables](external-comm/enet-tcp-udp/enet-member-var.md)
    * [6.2.3 Member Procedures](external-comm/enet-tcp-udp/enet-member-proc/README.md)
      * [open](external-comm/enet-tcp-udp/enet-member-proc/enet-open.md)
      * [connect](external-comm/enet-tcp-udp/enet-member-proc/enet-connect.md)
      * [send](external-comm/enet-tcp-udp/enet-member-proc/enet-end.md)
      * [recv](external-comm/enet-tcp-udp/enet-member-proc/enet-recv.md)
      * [close](external-comm/enet-tcp-udp/enet-member-proc/enet-close.md)
    * [6.2.4 Member Function](external-comm/enet-tcp-udp/enet-member-func/README.md)
      * [state](external-comm/enet-tcp-udp/enet-member-func/enet-state.md)
    * [6.2.5 Examples of TCP and UDP Communication](external-comm/enet-tcp-udp/enet-tcp-udp-example.md)
  * [6.3    Http\_Cli Module: HTTP Client](external-comm/http_cli/README.md)
    * [6.3.1 Constructor](external-comm/http_cli/http_cli-creator.md)
    * [6.3.2 Member Variables](external-comm/http_cli/http_cli-member-var.md)
    * [6.3.3 Member Procedure](external-comm/http_cli/http_cli-member-proc/README.md)
      * [get](external-comm/http_cli/http_cli-member-proc/http_cli-get.md)
      * [put](external-comm/http_cli/http_cli-member-proc/http_cli-put.md)
      * [post](external-comm/http_cli/http_cli-member-proc/http_cli-post.md)
      * [delete](external-comm/http_cli/http_cli-member-proc/http_cli-delete.md)
    * [6.3.4 Examples of HTTP Client Communication](external-comm/http_cli/http_cli-example.md)
  * [6.4 Getting input from console bar](external-comm/tp-console-bar-input/README.md)
    * [6.4.1 input](external-comm/tp-console-bar-input/input.md)

