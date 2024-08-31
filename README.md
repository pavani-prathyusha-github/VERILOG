Verilog is a hardware description language, it is used to describe digital system and circuits in the form of code. 
-> there are different levels of abstraction levels 
1) circuit level
2) gate level
3) Dataflow level
4) Behavioural level

how to write verilog?
 keywords - module and endmodule
 port declaration {input, output, inout} by default all are wire datatype
 functionality {assign  or procedures(i.e. initial and always)}

Datatypes 
-> net {wire, trireg,wor,wand}
-> register {reg, integer, real, time}

operators
-> logical (&&.||,!) evalutes to single bit(T,F,X)
-> bitwise (&,|,^,~)
-> reduction operator
-> concatenation {}
-> relational <=,>=
-> shift
-> equality
-> arithmetic 
-> conditional

system task
-> $display, $write, $strobe, $monitor

simulation control task
-> $stop, $finish

compiler directives
-> `include,`define, `timescale


