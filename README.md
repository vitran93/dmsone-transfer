#########################################
Development
1. [6.1.1]Bao cao san luong va doanh so ban hang theo nhan vien ban hang
- Java code: HoReportAction.report611 / HoReportMgr.report611
- SQL procedure: PKG_REPORT_SALE.P_REPORT_SALE_STAFF
- Notes:
2. [6.1.2]Doanh so theo tung khach hang
- Java code: HoReportAction.report12D8 / HoReportMgr.report12D8
- Jsp code: rpt_12_8.jsp
- SQL procedure: PKG_REPORT_SALE.P_REPORT_SALE_CUSTOMER
- Notes:
3. [1.1]Tong hop don hang phat sinh trong ngay
- Java code: HoReportAction.report1D1DSPSTN_V2 / HoReportMgr.report1D1DSPSTN_V2
- SQL procedure: PKG_REPORT_ORDER.P_REPORT_ORDER_PER_DAY
- Notes:
4. [4.1]Bao cao xuat nhap ton
- Java code: StockReportAction.exportXNTCT32 / HoReportMgr.exportXNTCT32
- Jsp code: 7_4_3.jsp
- SQL procedure: PKG_REPORT_STOCK.P_REPORT_STOCK_MOVEMENT
- Notes:
5. [6.1.4]Bao cao ban hang hang thang theo tuyen
- Java code: HoReportAction.report4D4D2 / HoReportMgr.report4D4D2
- Jsp code: rpt_4_4_2.jsp
- SQL procedure: PKG_REPORT_SALE.P_REPORT_SALE_STAFF_MONTH
- Notes:
6. [6.4.5]Bao cao raw data cac don dieu chinh
- Java code: HoReportAction.exportRawDataStockTrans_V2 / HoReportMgr.exportRawDataStockTrans
- SQL procedure: PKG_REPORT_STOCK.P_REPORT_STOCK_TRANS
- Notes:
7. [4.3]Bao cao xuat nhap ton chi tiet
- Java code: HoReportAction.reportV43 / HoReportMgr.reportV43
- Jsp code: rpt_4_3.jsp
- SQL procedure: PKG_REPORT_STOCK.P_REPORT_STOCK_MOVEMENT_TRANS / PKG_REPORT_STOCK.P_REPORT_STOCK_MOVEMENT_PROD
- SQL to get rsm, ams, nvbh: P_REPORT_STAFF_SHOP
- Notes: su dung 2 procedure tuy vao theo chung tu hay theo san pham
8. [6.4.4]Bao cao du lieu don hang
- Java code: HoReportAction.exportRawData / HoReportMgr.exportRawData
- SQL procedure: PKG_REPORT_ORDER.P_REPORT_SALE_ORDER_INFO
- Notes:
9. [12.12]Bao cao nvbh ghe tham kh
- Java code: HoReportAction.reportCusVisitForExcel / HoReportMgr.reportVisitCustomer
- SQL procedure: PKG_REPORT_SUPERVISION.P_REPORT_VISIT_CUSTOMER_DTL
- Notes:
10. [1.5]Bao cao chi tiet don hang
- Java code: HoReportAction.report1D5BCCTDH / HoReportMgr.report1D5BCCTDH
- SQL procedure: PKG_REPORT_ORDER.P_REPORT_SALE_ORDER_DETAIL_INFO
- Notes:
11. Chuong trinh khuyen mai
- Java code:PromotionCatalogAction.exportCTKM / RptPromotion
- SQL procedure: p_promotion_export
- XLSX template: 
- Notes:
#####################################
Deployment

#####################################
Setup develop enviroment
https://docs.google.com/document/d/1NcqDUbU3EAQqce6BY9KMOIobMgK-ZdygiqoExRdT2OU/edit?usp=sharing
