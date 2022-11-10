### Torsion angle

大二時做的蛋白質練習專案，主要可以分為下列幾個部分:

1. 讀取PDB檔案，並解析出原子位置
   原先使用Python內建讀取 → 改使用biopython的PDBParser
   因此相較原先只針對單一Chain，現在可以較完善的處理各個Chain
   
2. 從主鍊結構($-N-C_\alpha-C -$)，計算Torsion angle (兩面角)，
   
3. 再將計算出的Torsion angle進行回推驗算
