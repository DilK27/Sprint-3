import javafx.application.Application;
import java.util.List;
import java.util.ArrayList;
import javafx.collections.ObservableList;
import javafx.collections.FXCollections;



import javafx.scene.Scene;
import javafx.scene.Group;
import javafx.scene.control.TextArea;
import javafx.scene.control.Button;
import javafx.scene.control.Label;
import javafx.scene.control.ComboBox;
import javafx.scene.control.TextAreaBuilder;
import javafx.scene.control.Hyperlink;
import javafx.scene.control.TextField;
import javafx.scene.layout.VBox;
import javafx.scene.layout.BackgroundFill;
import javafx.scene.layout.Priority;
import javafx.scene.layout.StackPane;
import javafx.scene.shape.Rectangle;
import javafx.scene.shape.*;
import javafx.scene.shape.Box;
import javafx.scene.text.FontWeight;
import javafx.scene.text.Text;
import javafx.scene.paint.Color;
import javafx.scene.layout.GridPane;

import javafx.stage.Stage;

import java.awt.Font;

import java.io.Console;
import java.io.PrintStream;

import javafx.event.EventHandler;
import javafx.event.ActionEvent;

import javafx.geometry.Insets;

public class GUI extends Application {

    Stage window;
    static ChronoTimer Chrono;

    Scene OF;
    Scene ON;

    String racer = "";

    static TextArea resultArea = new TextArea();
    static TextArea stdoutArea = new TextArea();

    Button OFF;
    Button power1 = new Button("Power");
    Button power2 = new Button("Power");;
    Button function;
    Button swap;
    Button printer;

    Button b1 = new Button("   ");
    Button b2 = new Button("   ");
    Button b3 = new Button("   ");
    Button b4 = new Button("   ");
    Button b5 = new Button("   ");
    Button b6 = new Button("   ");
    Button b7 = new Button("   ");
    Button b8 = new Button("   ");

    Button round1 = new Button();
    Button round2 = new Button();
    Button round3 = new Button();
    Button round4 = new Button();
    Button round5 = new Button();
    Button round6 = new Button();
    Button round7 = new Button();
    Button round8 = new Button();
//    Button round1C = new Button();
//    Button round2C = new Button();
//    Button round3C = new Button();
//    Button round4C = new Button();
//    Button round5C = new Button();
//    Button round6C = new Button();
//    Button round7C = new Button();
//    Button round8C = new Button();
    Button usb = new Button();


    Button np0 = new Button("0");
    Button np1 = new Button("1");
    Button np2 = new Button("2");
    Button np3 = new Button("3");
    Button np4 = new Button("4");
    Button np5 = new Button("5");
    Button np6 = new Button("6");
    Button np7 = new Button("7");
    Button np8 = new Button("8");
    Button np9 = new Button("9");
    Button npstar = new Button("*");
    Button nphash = new Button("#");
    Button Larrow = new Button("←");
    Button Rarrow = new Button("→");
    Button Uarrow = new Button("↑");
    Button Darrow = new Button("↓");

    Label title = new Label("Chronotimer TEAM EZ");

    Label one = new Label("1");
    Label two = new Label("2");
    Label three = new Label("3");
    Label four = new Label("4");
    Label five = new Label("5");
    Label six = new Label("6");
    Label seven = new Label("7");
    Label eight = new Label("8");
    Label oneC = new Label("1");
    Label twoC = new Label("2");
    Label threeC = new Label("3");
    Label fourC = new Label("4");
    Label fiveC = new Label("5");
    Label sixC = new Label("6");
    Label sevenC = new Label("7");
    Label eightC = new Label("8");

    Label start = new Label("Start");
    Label enable1 = new Label("Enable/Disable");
    Label finish = new Label("Finish");
    Label enable2 = new Label("Enable/Disable");
    Label under = new Label("Queue / Running / Final Time");
    Label chan = new Label("CHAN");
    Label port = new Label("USB PORT");

    Line line1 = new Line(0, 500, 700, 500);


    Box print = new Box(150, 150, 150);
    Box screen = new Box(250, 200, 200);




    public static void main(String[] args) {

        launch(args);
        Chrono = new ChronoTimer();
    }

    public void start(Stage primaryStage) throws Exception {

        window = primaryStage;

        window.setTitle("ChronoTimer");

        ComboBox round1C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round1C.getSelectionModel().select(0);
        round1C.setId("changed");

        ComboBox round2C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round2C.getSelectionModel().select(0);
        round2C.setId("changed");

        ComboBox round3C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round3C.getSelectionModel().select(0);
        round3C.setId("changed");

        ComboBox round4C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round4C.getSelectionModel().select(0);
        round4C.setId("changed");

        ComboBox round5C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round5C.getSelectionModel().select(0);
        round5C.setId("changed");

        ComboBox round6C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round6C.getSelectionModel().select(0);
        round6C.setId("changed");

        ComboBox round7C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round7C.getSelectionModel().select(0);
        round7C.setId("changed");

        ComboBox round8C = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
        round8C.getSelectionModel().select(0);
        round8C.setId("changed");

//        ComboBox normalCombobox = new ComboBox<String>(FXCollections.observableArrayList("Gate", "Eye", "Pad"));
//        normalCombobox.getSelectionModel().select(0);



        // power1.setOnAction(e -> window.setScene(ON));
        power1.setTranslateX(10);
        power1.setTranslateY(10);

        // power2.setOnAction(e -> window.setScene(OF));
        power2.setTranslateX(10);
        power2.setTranslateY(10);

        function = new Button("Function");
        function.setTranslateX(10);
        function.setTranslateY(250);

        swap = new Button("Swap");
        swap.setTranslateX(10);
        swap.setTranslateY(400);

        printer = new Button("Printer");
        printer.setTranslateX(570);
        printer.setTranslateY(10);

        title.setTranslateX(275);
        title.setTranslateY(20);

        one.setTranslateX(257);
        one.setTranslateY(40);
        three.setTranslateX(307);
        three.setTranslateY(40);
        five.setTranslateX(357);
        five.setTranslateY(40);
        seven.setTranslateX(407);
        seven.setTranslateY(40);

        oneC.setTranslateX(63);
        oneC.setTranslateY(508);
        threeC.setTranslateX(103);
        threeC.setTranslateY(508);
        fiveC.setTranslateX(143);
        fiveC.setTranslateY(508);
        sevenC.setTranslateX(183);
        sevenC.setTranslateY(508);

        b1.setTranslateX(250);
        b1.setTranslateY(60);
        b3.setTranslateX(300);
        b3.setTranslateY(60);
        b5.setTranslateX(350);
        b5.setTranslateY(60);
        b7.setTranslateX(400);
        b7.setTranslateY(60);

        two.setTranslateX(257);
        two.setTranslateY(140);
        four.setTranslateX(307);
        four.setTranslateY(140);
        six.setTranslateX(357);
        six.setTranslateY(140);
        eight.setTranslateX(407);
        eight.setTranslateY(140);

        twoC.setTranslateX(63);
        twoC.setTranslateY(545);
        fourC.setTranslateX(103);
        fourC.setTranslateY(545);
        sixC.setTranslateX(143);
        sixC.setTranslateY(545);
        eightC.setTranslateX(183);
        eightC.setTranslateY(545);

        b2.setTranslateX(250);
        b2.setTranslateY(160);
        b4.setTranslateX(300);
        b4.setTranslateY(160);
        b6.setTranslateX(350);
        b6.setTranslateY(160);
        b8.setTranslateX(400);
        b8.setTranslateY(160);

        start.setTranslateX(200);
        start.setTranslateY(60);
        enable1.setTranslateX(150);
        enable1.setTranslateY(100);
        finish.setTranslateX(200);
        finish.setTranslateY(160);
        enable2.setTranslateX(150);
        enable2.setTranslateY(200);

        under.setTranslateX(210);
        under.setTranslateY(455);

//        combobox.setStyle("fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
//                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round1.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round2.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round3.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round4.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round5.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round6.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round7.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round8.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round1C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round2C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round3C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round4C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round5C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round6C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round7C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        round8C.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");

        np0.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np1.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np2.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np3.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np4.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np5.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np6.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np7.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np8.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        np9.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        npstar.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        nphash.setStyle(
                "-fx-min-width: 40px; " + "-fx-min-height: 40px; " + "-fx-max-width: 40px; " + "-fx-max-height: 40px;");

        Larrow.setStyle("-fx-font-size: 13px; " + "-fx-min-width: 35px; " + "-fx-min-height: 25px; "
                + "-fx-max-width: 35px; " + "-fx-max-height: 25px;");
        Rarrow.setStyle("-fx-font-size: 13px; " + "-fx-min-width: 35px; " + "-fx-min-height: 25px; "
                + "-fx-max-width: 35px; " + "-fx-max-height: 25px;");
        Uarrow.setStyle("-fx-font-size: 13px; " + "-fx-min-width: 30px; " + "-fx-min-height: 35px; "
                + "-fx-max-width: 30px; " + "-fx-max-height: 35px;");
        Darrow.setStyle("-fx-font-size: 13px; " + "-fx-min-width: 30px; " + "-fx-min-height: 35px; "
                + "-fx-max-width: 30px; " + "-fx-max-height: 35px;");
        usb.setStyle("-fx-min-width: 75px; " + "-fx-min-height: 20px; " + "-fx-max-width: 75px; "
                + "-fx-max-height: 20px;");


        screen.setTranslateX(300);
        screen.setTranslateY(350);

        print.setTranslateX(600);
        print.setTranslateY(125);

        usb.setTranslateX(100);
        usb.setTranslateY(600);

        port.setTranslateX(100);
        port.setTranslateY(600);

        np1.setTranslateX(520);
        np1.setTranslateY(300);
        np2.setTranslateX(560);
        np2.setTranslateY(300);
        np3.setTranslateX(600);
        np3.setTranslateY(300);
        np4.setTranslateX(520);
        np4.setTranslateY(340);
        np5.setTranslateX(560);
        np5.setTranslateY(340);
        np6.setTranslateX(600);
        np6.setTranslateY(340);
        np7.setTranslateX(520);
        np7.setTranslateY(380);
        np8.setTranslateX(560);
        np8.setTranslateY(380);
        np9.setTranslateX(600);
        np9.setTranslateY(380);
        npstar.setTranslateX(520);
        npstar.setTranslateY(420);
        np0.setTranslateX(560);
        np0.setTranslateY(420);
        nphash.setTranslateX(600);
        nphash.setTranslateY(420);

        Larrow.setTranslateX(15);
        Larrow.setTranslateY(325);
        Rarrow.setTranslateX(60);
        Rarrow.setTranslateY(325);
        Uarrow.setTranslateX(105);
        Uarrow.setTranslateY(325);
        Darrow.setTranslateX(140);
        Darrow.setTranslateY(325);

        round1.setTranslateX(257);
        round1.setTranslateY(100);
        round3.setTranslateX(307);
        round3.setTranslateY(100);
        round5.setTranslateX(357);
        round5.setTranslateY(100);
        round7.setTranslateX(407);
        round7.setTranslateY(100);

        round2.setTranslateX(257);
        round2.setTranslateY(200);
        round4.setTranslateX(307);
        round4.setTranslateY(200);
        round6.setTranslateX(357);
        round6.setTranslateY(200);
        round8.setTranslateX(407);
        round8.setTranslateY(200);

        round1C.setTranslateX(60);
        round1C.setTranslateY(525);
        round3C.setTranslateX(100);
        round3C.setTranslateY(525);
        round5C.setTranslateX(140);
        round5C.setTranslateY(525);
        round7C.setTranslateX(180);
        round7C.setTranslateY(525);

        chan.setTranslateX(10);
        chan.setTranslateY(515);

        usb.setTranslateX(400);
        usb.setTranslateY(530);

        port.setTranslateX(480);
        port.setTranslateY(530);


        round2C.setTranslateX(60);
        round2C.setTranslateY(563);
        round4C.setTranslateX(100);
        round4C.setTranslateY(563);
        round6C.setTranslateX(140);
        round6C.setTranslateY(563);
        round8C.setTranslateX(180);
        round8C.setTranslateY(563);

        Group off = new Group();
        Group on = new Group();

        resultArea.setTranslateX(200);
        resultArea.setTranslateY(250);
        resultArea.setPrefColumnCount(15);
        resultArea.setPrefRowCount(10);

        stdoutArea.setTranslateX(475);
        stdoutArea.setTranslateY(50);
        stdoutArea.setPrefColumnCount(15);
        stdoutArea.setPrefRowCount(10);



        Rectangle rect = new Rectangle(700, 500, Color.BLACK);
        off.getChildren().add(rect);
        off.getChildren().add(power1);

        Rectangle rekt = new Rectangle(700, 600, Color.LAVENDER);
        on.getChildren().add(rekt);

        on.getChildren().add(stdoutArea);
        on.getChildren().add(resultArea);
        on.getChildren().add(power2);
        on.getChildren().add(function);
        on.getChildren().add(swap);
        on.getChildren().add(printer);

        on.getChildren().add(title);

        on.getChildren().add(one);
        on.getChildren().add(two);
        on.getChildren().add(three);
        on.getChildren().add(four);
        on.getChildren().add(five);
        on.getChildren().add(six);
        on.getChildren().add(seven);
        on.getChildren().add(eight);

        on.getChildren().add(oneC);
        on.getChildren().add(twoC);
        on.getChildren().add(threeC);
        on.getChildren().add(fourC);
        on.getChildren().add(fiveC);
        on.getChildren().add(sixC);
        on.getChildren().add(sevenC);
        on.getChildren().add(eightC);

        on.getChildren().add(start);
        on.getChildren().add(enable1);
        on.getChildren().add(finish);
        on.getChildren().add(enable2);

        on.getChildren().add(b1);
        on.getChildren().add(b2);
        on.getChildren().add(b3);
        on.getChildren().add(b4);
        on.getChildren().add(b5);
        on.getChildren().add(b6);
        on.getChildren().add(b7);
        on.getChildren().add(b8);

        on.getChildren().add(round1);
        on.getChildren().add(round2);
        on.getChildren().add(round3);
        on.getChildren().add(round4);
        on.getChildren().add(round5);
        on.getChildren().add(round6);
        on.getChildren().add(round7);
        on.getChildren().add(round8);
        on.getChildren().add(chan);

        on.getChildren().add(round1C);
        on.getChildren().add(round2C);
        on.getChildren().add(round3C);
        on.getChildren().add(round4C);
        on.getChildren().add(round5C);
        on.getChildren().add(round6C);
        on.getChildren().add(round7C);
        on.getChildren().add(round8C);


        on.getChildren().add(np0);
        on.getChildren().add(np1);
        on.getChildren().add(np2);
        on.getChildren().add(np3);
        on.getChildren().add(np4);
        on.getChildren().add(np5);
        on.getChildren().add(np6);
        on.getChildren().add(np7);
        on.getChildren().add(np8);
        on.getChildren().add(np9);
        on.getChildren().add(npstar);
        on.getChildren().add(nphash);

        on.getChildren().add(Larrow);
        on.getChildren().add(Rarrow);
        on.getChildren().add(Uarrow);
        on.getChildren().add(Darrow);

        on.getChildren().add(under);
        on.getChildren().add(line1);

        on.getChildren().add(usb);
        on.getChildren().add(port);

        power1.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.setPower();
                reset();

                window.setScene(ON);
            }
        });

        power2.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.setPower();
                reset();
                stdoutArea.clear();
                resultArea.clear();
                window.setScene(OF);
            }
        });

        function.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.event("grp");
                Chrono.newRun();
            }
        });

        swap.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (Chrono.event.equalsIgnoreCase("IND")) {
                    if (Chrono.toFinish.size() >= 2) {
                        stdoutArea.appendText("You are able to swap\n");
                        int tmp = Chrono.toFinish.get(0).index;
                        Chrono.toFinish.get(0).index = Chrono.toFinish.get(1).index;
                        Chrono.toFinish.get(1).index = tmp;

                        Racer temp = Chrono.toFinish.removeFirst();
                        Chrono.toFinish.add(1, temp);
                    }
                    else {
                        stdoutArea.appendText("Not enough racers to swap\n");
                    }
                }
                else {
                    stdoutArea.appendText("Can only use this feature in event IND\n");
                }
            }
        });

        b1.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(1);
                Chrono.updScreen();
            }
        });

        b2.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(2);
                Chrono.updScreen();
            }
        });

        b3.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(3);
                Chrono.updScreen();
            }
        });

        b4.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(4);
                Chrono.updScreen();
            }
        });

        b5.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(5);
                Chrono.updScreen();
            }
        });

        b6.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(6);
                Chrono.updScreen();
            }
        });

        b7.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(7);
                Chrono.updScreen();
            }
        });

        b8.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.trigChannel(8);
                Chrono.updScreen();
            }
        });

        round1.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(1);
                if (Chrono.channels[1]) {
                    round1.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round1.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        round2.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(2);
                if (Chrono.channels[2]) {
                    round2.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round2.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        round3.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(3);
                if (Chrono.channels[3]) {
                    round3.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round3.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        round4.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(4);
                if (Chrono.channels[4]) {
                    round4.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round4.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        round5.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(5);
                if (Chrono.channels[5]) {
                    round5.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round5.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        round6.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(6);
                if (Chrono.channels[6]) {
                    round6.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round6.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        round7.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(7);
                if (Chrono.channels[7]) {
                    round7.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round7.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        round8.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                Chrono.togChannel(8);
                if (Chrono.channels[8]) {
                    round8.setStyle("-fx-background-color: lawngreen; " + "-fx-background-radius: 80em; "
                            + "-fx-min-width: 16px; " + "-fx-min-height: 16px; " + "-fx-max-width: 16px; "
                            + "-fx-max-height: 16px;");
                } else {
                    round8.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                            + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
                }
            }
        });

        np1.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("1");
                    racer = racer.concat("1");
                } else {
                    Chrono.event("ind");
                }
            }
        });

        np2.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("2");
                    racer = racer.concat("2");
                } else {
                    Chrono.event("parind");
                }
            }
        });

        np3.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("3");
                    racer = racer.concat("3");
                } else {
                    Chrono.event("grp");
                }
            }
        });

        np4.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("4");
                    racer = racer.concat("4");
                }

            }
        });

        np5.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("5");
                    racer = racer.concat("5");
                }
            }
        });

        np6.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("6");
                    racer = racer.concat("6");
                }
            }
        });

        np7.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("7");
                    racer = racer.concat("7");
                }
            }
        });

        np8.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("8");
                    racer = racer.concat("8");
                }
            }
        });

        np9.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("9");
                    racer = racer.concat("9");
                }
            }
        });

        np0.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    stdoutArea.appendText("0");
                    racer = racer.concat("0");
                }
            }
        });

        npstar.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    if (Chrono.run) {
                        Chrono.endrun();
                        reset();
                    } else {
                        Chrono.newRun();
                    }
                }
            }
        });

        nphash.setOnAction(new EventHandler<ActionEvent>() {
            public void handle(ActionEvent event) {
                if (!Chrono.event.isEmpty()) {
                    if(!racer.isEmpty()){
                        if(!Chrono.out) {
                            stdoutArea.appendText("\n");
                            Chrono.num(Integer.parseInt(racer));
                            racer = "";
                        } else {
                            Chrono.updGRPF(racer);
                            racer = "";
                        }
                    }
                }

            }
        });

        printer.setOnAction(new EventHandler<ActionEvent>() {
            @Override
            public void handle(ActionEvent event) {
                ChronoTimer.printlists();
            }
        });

//        round1C.setOnAction(new EventHandler<ActionEvent>() {
//            @Override
//            public void handle(ActionEvent event) {
//                comboBox.isPressed();
//            }
//        });

        OF = new Scene(off, 700, 500);
        ON = new Scene(on, 700, 600);
        window.setScene(OF);
        window.show();
    }

    public void reset() {
        round1.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
        round2.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
        round3.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
        round4.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
        round5.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
        round6.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
        round7.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
        round8.setStyle("-fx-background-radius: 80em; " + "-fx-min-width: 16px; " + "-fx-min-height: 16px; "
                + "-fx-max-width: 16px; " + "-fx-max-height: 16px;");
    }
}
