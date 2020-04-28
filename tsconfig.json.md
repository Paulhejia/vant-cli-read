{
  "compilerOptions": {
    "target": "ES2017",
    "outDir": "./lib",
    "module": "commonjs",
    "strict": true,
    "declaration": true, // 生成相应的 .d.ts文件。
    "skipLibCheck": true, // 忽略所有的声明文件（ *.d.ts）的类型检查。
    "esModuleInterop": true, // 允许从没有设置默认导出的模块中默认导入。这并不影响代码的输出，仅为了类型检查。
    "lib": ["esnext", "dom"] // 	编译过程中需要引入的库文件的列表。     
  },
  "include": ["src/**/*", "site"]
}
